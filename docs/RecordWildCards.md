# Packages that use the `RecordWildCard` extension

## `auxx` package
| File | Types | Type Definition Location |
| --- | --- | ---|
|src/Plugin.hs|AuxxOptions| auxx/src/AuxxOptions.hs|
|src/Plugin.hs|WithCommandAction|auxx/src/Repl.hs|
|src/Plugin.hs|SendActions|infra/src/Pos/Infra/Communication/Types/Protocol.hs|
|src/Plugin.hs|ConversationActions|networking/src/Node/Conversation.hs|
|src/Lang/Lexer.hs|SourcePos| Megaparsec|
|src/Lang/Lexer.hs|BlockVersion|core/src/Pos/Core/Update/BlockVersion.hs|
|src/Lang/Lexer.hs|SoftwareVersion |core/src/Pos/Core/Update/SoftwareVersion.hs|
|src/Lang/Argument.hs|ArgumentError| Same module|
|src/Lang/Argument.hs|ProcError| Same module|
|src/Lang/DisplayError.hs|TypeError|auxx/src/Lang/Argument.hs|
|src/Lang/DisplayError.hs|ArgumentError|auxx/src/Lang/Argument.hs|
|src/Lang/DisplayError.hs|ProcError|auxx/src/Lang/Argument.hs|
|src/Lang/DisplayError.hs|Report | Earley |
|src/Lang/Interpreter.hs|CommandProc|auxx/src/Lang/Command.hs|
|src/Command/Help.hs|CommandProc|auxx/src/Lang/Command.hs|
|src/Command/Help.hs|UnavailableCommand|auxx/src/Lang/Command.hs|
|src/Command/Update.hs|ProposeUpdateParams|auxx/src/Lang/Value.hs|
|src/Command/Update.hs|ProposeUpdateSystem|auxx/src/Lang/Value.hs|
|src/Command/BlockGen.hs|GenBlocksParams|auxx/src/Lang/Value.hs|
|src/AuxxOptions.hs|AuxxOptions | Same module|
|src/Repl.hs|WithCommandAction| Same module|
|src/Command/Proc.hs|TxOut|core/src/Pos/Core/Txp/TxOutAux.hs|
|src/Command/Proc.hs|SendToAllGenesisParams|auxx/src/Command/Tx.hs|
|src/Command/Proc.hs|BlockVersionModifier|core/src/Pos/Core/Update/BlockVersionModifier.hs |
|src/Command/Proc.hs|ProposeUpdateSystem|auxx/src/Lang/Value.hs|
|src/Command/Proc.hs|SoftwareVersion|core/src/Pos/Core/Update/SoftwareVersion.hs|
|src/Command/Proc.hs|ProposeUpdateParams|auxx/src/Lang/Value.hs|
|src/Command/Proc.hs|GenBlocksParams|auxx/src/Lang/Value.hs|
|src/Command/Proc.hs|AddKeyParams |auxx/src/Lang/Value.hs
|src/Command/Proc.hs|RollbackParams|auxx/src/Lang/Value.hs|
|Main.hs|AuxxOptions |auxx/src/AuxxOptions.hs|
|Main.hs|NodeContext |lib/src/Pos/Context/Context.hs|
|Main.hs|CommonNodeArgs |lib/src/Pos/Client/CLI/NodeOptions.hs|


## `binary` package
### File path prefix: src/Pos/Binary/
| File | Types | Type Definition Location |
| --- | --- | ---|
|Class/TH.hs|DataCon| th-utilities|
|Class/TH.hs|Cons| Same module|
|Class/TH.hs|Field| Same module

### File path prefix: test/Test/Pos/

| File | Types | Type Definition Location |
| --- | --- | ---|
Binary/Helpers.hs|SizeTestConfig|Same module|

## `chain` package
### File path prefix: src/Pos/Chain/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Update/Configuration.hs|UpdateConfiguration| Same module |
|Update/Poll/Failure.hs|PollVerFailure (PollTipMismatch)| Same module |
|Update/Poll/Types.hs|UndecidedProposalState| Same module |
|Update/BlockVersion.hs|BlockVersionData, BlockVersionModifier| core/src/Pos/Core/Update/BlockVersionModifier.hs |
|Update/Poll/Class.hs|SoftwareVersion | core/src/Pos/Core/Update/SoftwareVersion.hs |
|Update/Poll/Class.hs|UpdateProposal (UnsafeUpdateProposal) | core/src/Pos/Core/Update/Vote.hs |
|Block/Genesis/Instances.hs|GenericBlock b (UnsafeGenericBlock) | chain/src/Pos/Chain/Block/Blockchain.hs |
|Block/Genesis/Instances.hs|GenesisBody | chain/src/Pos/Chain/Block/Genesis/Types.hs |
|Block/Genesis/Types.hs|GenesisBody, GenesisConsensusData | Same module |
|Block/Main/Instances.hs|UnsafeGenericBlock | chain/src/Pos/Chain/Block/Blockchain.hs|
|Block/Main/Instances.hs|MainBody |chain/src/Pos/Chain/Block/Main/Types.hs|
|Block/JsonLog.hs|JLBlock |core/src/Pos/Core/JsonLog/LogEvents.hs|
|Block/Main/Types.hs|MainBody, MainExtraHeaderData, MainProof|Same module|
|Block/Logic/Integrity.hs|VerifyBlockParams, VerifyHeaderParams |Same module|
|Block/Types.hs|Undo|Same module|
|Block/BHelpers.hs|UnsafeGenericBlock |chain/src/Pos/Chain/Block/Blockchain.hs|
|Block/BHelpers.hs|MainBody |chain/src/Pos/Chain/Block/Main/Types.hs|
|Block/BHelpers.hs|GenericBlockHeader b (UnsafeGenericBlockHeader) |chain/src/Pos/Chain/Block/Blockchain.hs|
|Block/BHelpers.hs|MainConsensusData|chain/src/Pos/Chain/Block/Union/Types.hs|
|Block/BHelpers.hs|MainExtraHeaderData |chain/src/Pos/Chain/Block/Main/Types.hs|
|Delegation/Types.hs|DlgUndo|chain/src/Pos/Chain/Delegation/Types.hs|
|Block/Blockchain.hs|GenericBlockHeader b (UnsafeGenericBlockHeader), GenericBlock b (UnsafeGenericBlock) | Same module
|Block/Union/Types.hs|GenericBlockHeader b (UnsafeGenericBlockHeader) |chain/src/Pos/Chain/Block/Blockchain.hs|
|Block/Union/Types.hs|GenesisConsensusData |chain/src/Pos/Chain/Block/Genesis/Types.hs|
|Block/Union/Types.hs|MainBody|chain/src/Pos/Chain/Block/Main/Types.hs|
|Block/Union/Types.hs|MainConsensusData |Same module|
|Txp/Toil/Stakes.hs|UnsafeTx |core/src/Pos/Core/Txp/Tx.hs|
|Txp/Base.hs|TxOutAux |core/src/Pos/Core/Txp/TxOutAux.hs|
|Txp/Base.hs|TxOut |core/src/Pos/Core/Txp/Tx.hs|
|Txp/Base.hs|UnsafeTxPayload |core/src/Pos/Core/Txp/TxPayload.hs|
|Txp/Toil/Logic.hs|VerifyTxUtxoRes |chain/src/Pos/Chain/Txp/Toil/Utxo/Functions.hs|
|Txp/Toil/Logic.hs|BlockVersionData |core/src/Pos/Core/Update/BlockVersionData.hs|
|Txp/Toil/Logic.hs|TxAux |core/src/Pos/Core/Txp/TxAux.hs|
|Txp/Toil/Logic.hs|AddrAttributes |core/src/Pos/Core/Common/AddrAttributes.hs|
|Security/Util.hs|SecurityParams|chain/src/Pos/Chain/Security/Params.hs|
|Txp/Toil/Failure.hs|TxOut |core/src/Pos/Core/Txp/Tx.hs|
|Ssc/Shares.hs|Commitment |core/src/Pos/Core/Ssc/Commitment.hs|
|Txp/Topsort.hs|TxAux |core/src/Pos/Core/Txp/TxAux.hs|
|Txp/Toil/Utxo/Functions.hs|VTxContext | Same module|
|Txp/Toil/Utxo/Functions.hs|TxOut, UnsafeTx |core/src/Pos/Core/Txp/Tx.hs|
|Txp/Toil/Utxo/Functions.hs|TxAux |core/src/Pos/Core/Txp/TxAux.hs|
|Ssc/Toss/Logic.hs|TossModifier |chain/src/Pos/Chain/Ssc/Toss/Types.hs|
|Ssc/Base.hs|Commitment |core/src/Pos/Core/Ssc/Commitment.hs|
|Ssc/Error/Verify.hs|SscVerifyError (TossInternalError)| Same module|
|Ssc/Seed.hs|Commitment|core/src/Pos/Core/Ssc/Commitment.hs|
|Ssc/Types.hs|SscGlobalState, SscParams |Same module|
|Ssc/VssCertData.hs|VssCertData |Same module|
|Ssc/Toss/Base.hs|Commitment|core/src/Pos/Core/Ssc/Commitment.hs|
|bench/block-bench.hs|TestSubject| Same module|

### File path prefix: test/Test/Pos/Chain

| File | Types | Type Definition Location |
| --- | --- | ---|
|Txp/CoreSpec.hs|UnsafeTx | core/src/Pos/Core/Txp/TxPayload.hs|
|Ssc/Arbitrary.hs|Commitment | core/src/Pos/Core/Ssc/Commitment.hs|
|Ssc/Arbitrary.hs|SlotId|core/src/Pos/Core/Slotting/SlotId.hs|
|Block/Arbitrary.hs|MainProof |src/Pos/Chain/Block/Main/Types.hs|
|Block/Arbitrary.hs|BodyDependsOnSlot | Same module|
|Block/Arbitrary.hs|SlotId|core/src/Pos/Core/Slotting/SlotId.hs|
|Txp/Toil/UtxoSpec.hs|UnsafeTx|core/src/Pos/Core/Txp/Tx.hs|
|Txp/Toil/UtxoSpec.hs|TxOutAux|core/src/Pos/Core/Txp/TxOutAux.hs|
|Txp/Toil/UtxoSpec.hs|ToilVerFailure (ToilWitnessDoesntMatch)|chain/src/Pos/Chain/Txp/Toil/Failure.hs|

## `core` package
### File path prefix: src/Pos/Core/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Genesis/Data.hs|GenesisData |Same module
|Genesis/Canonical.hs|SchemaError| Same module
|Genesis/Initializer.hs|GenesisInitializer |Same module
|Genesis/Initializer.hs|TestnetBalanceOptions |Same module
|Genesis/Generate.hs|GenesisInitializer|core/src/Pos/Core/Genesis/Initializer.hs
|Genesis/Generate.hs|TestnetBalanceOptions|core/src/Pos/Core/Genesis/Initializer.hs
|Genesis/Generate.hs|RichSecrets |Same module
|Genesis/Generate.hs|FakeAvvmOptions|core/src/Pos/Core/Genesis/Initializer.hs
|Update/Payload.hs|UpdatePayload |Same module
|Configuration.hs|CoreConfiguration|src/Pos/Core/Configuration/Core.hs
|Configuration.hs|GenesisConfiguration (GCSrc)|src/Pos/Core/Configuration/Core.hs
|Configuration.hs|GeneratedGenesisData |src/Pos/Core/Genesis/Generate.hs
|Update/BlockVersionModifier.hs|BlockVersionModifier | Same module
|Update/Data.hs|UpdateData  | Same module
|Genesis/ProtocolConstants.hs|GenesisProtocolConstants | Same module
|Genesis/ProtocolConstants.hs|ProtocolConstants |src/Pos/Core/ProtocolConstants.hs
|Update/SoftforkRule.hs|SoftforkRule |Same module
|Update/BlockVersion.hs|BlockVersion |Same module
|Update/SoftwareVersion.hs|SoftwareVersion |Same module
|Update/Vote.hs|UnsafeUpdateProposal  | Same module
|Update/Vote.hs|UnsafeUpdateVote |Same module
|Update/Util.hs|BlockVersionModifier |src/Pos/Core/Update/BlockVersionModifier.hs
|Update/Util.hs|SoftforkRule |src/Pos/Core/Update/SoftforkRule.hs
|Update/Util.hs|UnsafeUpdateProposal |src/Pos/Core/Update/Vote.hs
|Reporting/MemState.hs|MisbehaviorMetrics|Same module
|Update/BlockVersionData.hs|BlockVersionData |Same module
|Attributes.hs|Attributes| Same module
|Reporting/Metrics.hs|MetricMonitorState  | Same module
|Reporting/Metrics.hs|MetricMonitor | Same module
|Update/Types.hs|SoftwareVersion |src/Pos/Core/Update/SoftwareVersion.hs
|Update/Types.hs|BlockVersion |src/Pos/Core/Update/BlockVersion.hs
|Update/Types.hs|SoftforkRule |src/Pos/Core/Update/SoftforkRule.hs
|Update/Types.hs|BlockVersionData |src/Pos/Core/Update/BlockVersionData.hs
|Update/Types.hs|BlockVersionModifier |src/Pos/Core/Update/BlockVersionModifier.hs
|Update/Types.hs|UnsafeUpdateProposal |src/Pos/Core/Update/Vote.hs
|Update/Types.hs|UpdateData |src/Pos/Core/Update/Data.hs
|Update/Types.hs|UnsafeUpdateVote |src/Pos/Core/Update/Vote.hs
|Update/Types.hs|UpdatePayload |src/Pos/Core/Update/Payload.hs
|Delegation/HeavyDlgIndex.hs|UnsafeProxySecretKey|crypto/Pos/Crypto/Signing/Types/Signing.hs
|Txp/TxAux.hs|TxAux|core/src/Pos/Core/Txp/TxAux.hs
|Txp/TxProof.hs|UnsafeTxPayload |core/src/Pos/Core/Txp/TxPayload.hs
|Txp/TxPayload.hs|UnsafeTxPayload |core/src/Pos/Core/Txp/TxPayload.hs
|Ssc/Commitment.hs|Commitment|core/src/Pos/Core/Ssc/Commitment.hs
|Txp/TxWitness.hs|TxSigData | Same module
|Ssc/VssCertificate.hs|UnsafeVssCertificate | Same module
|Txp/Tx.hs|UnsafeTx|Same module
|Txp/Tx.hs|TxOut |Same module
|Common/Script.hs|Script | Same module
|Common/TxFeePolicy.hs|TxFeePolicyUnknown {}|Same module
|Common/AddrAttributes.hs|AddrAttributes |Same module
|Slotting/TimeDiff.hs|TimeDiff|Same module
|Slotting/SlotId.hs|SlotId |Same module
|Common/Address.hs|AddrAttributes |core/src/Pos/Core/Common/Address.hs
|Common/Address.hs|AddrType (ATUnknown)| core/src/Pos/Core/Common/AddrSpendingData.hs
|Common/Address.hs|AddrAttributes |core/src/Pos/Core/Common/Address.hs
|Common/Address.hs|Address|Same module
|Slotting/Timestamp.hs|Timestamp|Same module
|Slotting/Util.hs|EpochSlottingData |core/src/Pos/Core/Slotting/Types.hs
|Slotting/EpochOrSlot.hs|SlotId |src/Pos/Core/Slotting/SlotId.hs

### File path prefix: test/Test/Pos/Core/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Arbitrary/Unsafe.hs|Address |core/src/Pos/Core/Common/Address.hs|
|Arbitrary.hs|TestnetBalanceOptions |core/src/Pos/Core/Genesis/Initializer.hs|
|Arbitrary.hs|FakeAvvmOptions |core/src/Pos/Core/Genesis/Initializer.hs|
|Arbitrary.hs|TxFeePolicyTxSizeLinear|core/src/Pos/Core/Common/TxFeePolicy.hs|

## `crypto` package
### File path prefix: Pos/Crypto/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Scrypt.hs|ScryptParamsBuilder |Same module|
|SafeCopy.hs|ProxySignature|crypto/Pos/Crypto/Signing/Types/Signing.hs|
|Signing/Types/Signing.hs|UnsafeProxySecretKey | Same module|
|Signing/Types/Signing.hs|ProxySignature|crypto/Pos/Crypto/Signing/Types/Signing.hs|
|SecretSharing.hs|SecretProof| Same module|
|Signing/Signing.hs|ProxySignature|crypto/Pos/Crypto/Signing/Types/Signing.hs|

### File path prefix: test/Test/Pos/Crypto/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Arbitrary.hs|SharedSecrets| Same module|
|CryptoSpec2.hs|UnsafeProxySecretKey|crypto/Pos/Crypto/Signing/Types/Signing.hs|

## `networking` package
### File path prefix: src/Network/
| File | Types | Type Definition Location |
| --- | --- | ---|
|QDisc/Fair.hs|FairQDisc|Same module|
|QDisc/Simulation.hs|SimulationParameters| Same module|
|QDisc/Simulation.hs|Scenario| Same module|
|Broadcast/OutboundQueue/Types.hs|Peers | Same module|
|Broadcast/OutboundQueue/Types.hs|Routes| Same module|
|Broadcast/OutboundQueue/Demo.hs|Node| Same module|
|Broadcast/OutboundQueue/Demo.hs|MsgObj| Same module|
|Broadcast/OutboundQueue/Demo.hs|NodeId| Same module|
|Broadcast/OutboundQueue/ConcurrentMultiQueue.hs|MultiQueue| Same module|
|Broadcast/OutboundQueue.hs|Packet| Same module|
|Broadcast/OutboundQueue.hs|OutQ | Same module|
|Broadcast/OutboundQueue.hs|QHealth | Same module|
|Broadcast/OutboundQueue.hs|NodeWithStats| Same module|
|Broadcast/OutboundQueue.hs|ThreadRegistry (TR)| Same module|
|Broadcast/OutboundQueue.hs|Signal| Same module|

### File path prefix: none
| File | Types | Type Definition Location |
| --- | --- | ---|
|src/Node/Message/Class.hs|Packing | Same module|
|src/Ntp/Packet.hs|NtpPacket| Same module|
|src/Node/Internal.hs|Node| Same module|
|src/Node/Internal.hs|PeerStatistics| Same module|
|src/Bench/Network/Commons.hs|MeasureInfo|Same module|
|src/Ntp/Client.hs|NtpConfiguration |Same module|
|src/Ntp/Client.hs|NtpClient|Same module|
|bench/Receiver/Main.hs|Args |networking/bench/Receiver/ReceiverOptions.hs|
|bench/Sender/Main.hs|Args |networking/bench/Receiver/ReceiverOptions.hs|
|bench/LogReader/Main.hs|MeasureInfo|src/Bench/Network/Commons.hs|
|bench/LogReader/Main.hs|Args|networking/bench/Receiver/ReceiverOptions.hs|
|test/Test/NtpSpec.hs|NtpPacket |src/Ntp/Packet.hs|
|test/Test/NtpSpec.hs|NtpPacketWithOffset| Same module|
|test/Test/Network/Broadcast/OutboundQueueSpec.hs|Peers|src/Network/Broadcast/OutboundQueue/Types.hs|
|test/Test/Util.hs|TestState|Same module|


## `util` package
### File path prefix: Pos/Util/
| File | Types | Type Definition Location |
| --- | --- | ---|
|CompileInfo.hs|CompileTimeInfo|Same module|
|Timer.hs|Timer|Same module|