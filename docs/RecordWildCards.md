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

## `client` package
### File path prefix: src/Pos/Client/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Txp/Network.hs|TxAux |core/src/Pos/Core/Txp/TxAux.hs|
|Txp/History.hs|UnsafeTx |core/src/Pos/Core/Txp/TxPayload.hs|
|Txp/History.hs|TxHistoryEntry (THEntry) | Same module|
|Txp/Util.hs|WalletError (NotEnoughMoney)|wallet-new/src/Cardano/Wallet/API/V1/Errors.hs|
|Txp/Util.hs|TxError(NotEnoughAllowedMoney| Same module|
|Txp/Util.hs|TxError (FailedToStabilize)||
|Txp/Util.hs|WalletError (OutputIsRedeem)|wallet-new/src/Cardano/Wallet/API/V1/Errors.hs|
|Txp/Util.hs|TxError (RedemptionDepleted)|Same module|
|Txp/Util.hs|TxError(SafeSignerNotFound|Same module|
|Txp/Util.hs|TxError (SignedTxNotBase16Format)| Same module|
|Txp/Util.hs|TxError (SignedTxUnableToDecode)| Same module|
|Txp/Util.hs|TxError (SignedTxSignatureNotBase16Format)|Same module|
|Txp/Util.hs|TxError (SignedTxInvalidSignature)|Same module|
|Txp/Util.hs|TxError (GeneralTxError)|Same module|
|Txp/Util.hs|TxCreatorData|Same module|
|Txp/Util.hs|TxOut |core/src/Pos/Core/Txp/TxOutAux.hs|
|Txp/Util.hs|UtxoGroup |Same module|
|Txp/Util.hs|TxRaw | Same module|

### File path prefix: test/Test/Pos/Core/

| File | Types | Type Definition Location |
| --- | --- | ---|
Client/Txp/UtilSpec.hs|CreateMTxParams|Same module|
Client/Txp/UtilSpec.hs|CreateRedemptionTxParams|Same module|

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
|Common/TxFeePolicy.hs|TxFeePolicyUnknown |Same module
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

## `db` package
### File path prefix: src/Pos/DB/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Update/Poll/Logic/Softfork.hs|BlockVersionState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Softfork.hs|BlockVersionData |core/src/Pos/Core/Update/Types.hs|
|Update/Poll/Logic/Version.hs|UnsafeUpdateProposal |src/Pos/Core/Update/Vote.hs|
|Update/Logic/Local.hs|MemState |db/src/Pos/DB/Update/MemState/Types.hs|
|Update/Logic/Local.hs|MemPool |db/src/Pos/DB/Update/MemState/Types.hs|
|Update/Logic/Local.hs|SlotId|src/Pos/Core/Slotting/SlotId.hs|
|Update/Poll/Logic/Apply.hs|UpdatePayload |src/Pos/Core/Update/Payload.hs|
|Update/Poll/Logic/Apply.hs|UnsafeUpdateProposal |src/Pos/Core/Update/Vote.hs|
|Update/Poll/Logic/Apply.hs|UndecidedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Apply.hs|BlockVersionData |core/src/Pos/Core/Update/Types.hs|
|Update/Poll/Logic/Apply.hs|DecidedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Apply.hs|DpsExtra |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Apply.hs|UpsExtra |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Logic/Global.hs|PollModifier |chain/src/Pos/Chain/Update/Poll/Modifier.hs|
|Update/Poll/Logic/Base.hs|BlockVersion |src/Pos/Core/Update/BlockVersion.hs|
|Update/Poll/Logic/Base.hs|SoftforkRule |src/Pos/Core/Update/SoftforkRule.hs|
|Update/Poll/Logic/Base.hs|UndecidedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Rollback.hs|SoftwareVersion |src/Pos/Core/Update/SoftwareVersion.hs|
|Update/Poll/PollState.hs|PollModifier |chain/src/Pos/Chain/Update/Poll/Modifier.hs|
|Update/Poll/PollState.hs|PollState |db/src/Pos/DB/Update/Poll/PollState.hs|
|Update/GState.hs|SoftwareVersion |src/Pos/Core/Update/SoftwareVersion.hs|
|Update/GState.hs|ConfirmedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Normalize.hs|UndecidedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Logic/Normalize.hs|DecidedProposalState |chain/src/Pos/Chain/Update/Poll/Types.hs|
|Update/Poll/Pure.hs|SoftwareVersion |src/Pos/Core/Update/SoftwareVersion.hs|
|Update/MemState/Functions.hs|UpdatePayload |src/Pos/Core/Update/Payload.hs|
|Block/Slog/Context.hs|SlogGState |chain/src/Pos/Chain/Block/Slog/Types.hs|
|Block/Slog/Context.hs|SlogContext |chain/src/Pos/Chain/Block/Slog/Types.hs|
|Block/Slog/Context.hs|SlogGState |chain/src/Pos/Chain/Block/Slog/Types.hs|
|Update/MemState/Types.hs|MemState|db/src/Pos/DB/Update/MemState/Types.hs|
|Rocks/Functions.hs|NodeDBs |db/src/Pos/DB/Rocks/Types.hs|
|Rocks/Functions.hs|DB |db/src/Pos/DB/Rocks/Types.hs|
|Block/Slog/Logic.hs|BlockVersion |src/Pos/Core/Update/BlockVersion.hs|
|Block/Logic/Types.hs|VerifyBlocksContext | Same module|
|Block/Logic/Internal.hs|TxpGlobalSettings |db/src/Pos/DB/Txp/Settings.hs|
|Block/Logic/VAR.hs|TxpGlobalSettings |db/src/Pos/DB/Txp/Settings.hs|
|Delegation/Logic/VAR.hs|DlgUndo|chain/src/Pos/Chain/Delegation/Types.hs|
|Txp/Logic/Local.hs|ToilVerFailure |chain/src/Pos/Chain/Txp/Toil/Failure.hs|
|Txp/Logic/Local.hs|LocalToilState |chain/src/Pos/Chain/Txp/Toil/Monad.hs|
|Txp/Logic/Local.hs|TxpLocalData|db/src/Pos/DB/Txp/MemState/Types.hs|
|Txp/Logic/Global.hs|ProcessBlundsSettings |db/src/Pos/DB/Txp/Logic/Global.hs|
|Txp/Logic/Global.hs|GlobalToilState |chain/src/Pos/Chain/Txp/Toil/Monad.hs|
|GState/Lock.hs|StateLockMetrics |db/src/Pos/DB/GState/Lock.hs|
|Ssc/SecretStorage.hs|SscSecretStorage |chain/src/Pos/Chain/Ssc/Types.hs|
|Ssc/Logic/Local.hs|SlotId |src/Pos/Core/Slotting/SlotId.hs|
|Lrc/Context.hs|LrcContext | Same module|
|Lrc/Context.hs|LrcSyncData | Same module|
|BatchOp.hs|DB |db/src/Pos/DB/Rocks/Types.hs|

## `explorer` package
### File path prefix: src/Pos/Explorer/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Txp/Common.hs|UnsafeTx |src/Pos/Core/Txp/Tx.hs|
|Txp/Toil/Logic.hs|BalanceUpdate |Same module|
|Txp/Toil/Logic.hs|UnsafeTx |src/Pos/Core/Txp/Tx.hs|
|ExplorerMode.hs|TestParams |generator/src/Test/Pos/Block/Logic/Mode.hs|
|ExplorerMode.hs|LrcContext |db/src/Pos/DB/Lrc/Context.hs|
|ExplorerMode.hs|GStateContext DBSum|db/src/Pos/DB/Sum.hs|
|ExplorerMode.hs|ExplorerTestContext |Same module|
|Socket/App.hs|NotifierSettings|Same module|
|Socket/Methods.hs|SubscriptionParam|Same module|
|Socket/Methods.hs|TxExtra |explorer/src/Pos/Explorer/Core/Types.hs|
|Web/ClientTypes.hs|Undo|src/Pos/Chain/Block/Types.hs|
|Web/ClientTypes.hs|CBlockEntry |Same module|
|Web/ClientTypes.hs|CTxEntry |Same module|
|Web/ClientTypes.hs|CBlockSummary |Same module|
|Web/ClientTypes.hs|TxInternal|Same module|
|Web/ClientTypes.hs|CTxBrief |Same module|
|Web/Server.hs|Address |core/src/Pos/Core/Common/Address.hs|
|Web/Server.hs|AddrType (ATUnknown) {}|core/src/Pos/Core/Common/AddrSpendingData.hs|
|Web/Server.hs|GenesisSummaryInternal |Same module|
|Web/Server.hs|CGenesisAddressInfo|explorer/src/Pos/Explorer/Web/ClientTypes.hs|
|Web/Server.hs|TxExtra |explorer/src/Pos/Explorer/Core/Types.hs|

### File path prefix: src/explorer/

| File | Types | Type Definition Location |
| --- | --- | ---|
|ExplorerNodeOptions.hs|ExplorerArgs|Same module|
|Main.hs|CommonNodeArgs|lib/src/Pos/Client/CLI/NodeOptions.hs|
|Main.hs|ExplorerArgs|explorer/src/explorer/ExplorerNodeOptions.hs|
|Main.hs|NodeResources |lib/src/Pos/Launcher/Resource.hs|
|Main.hs|NodeContext lib/src/Pos/Context/Context.hs|

### File path prefix: none

| File | Types | Type Definition Location |
| --- | --- | ---|
|src/purescript/Main.hs|Args |/explorer/src/purescript/PSOptions.hs|


## `infra` package
### File path prefix: src/Pos/Infra/

| File | Types | Type Definition Location |
| --- | --- | ---|
|Reporting/Ekg.hs|EkgParams |src/Pos/Infra/Statistics/Ekg.hs|
|Reporting/Statsd.hs|StatsdParams |src/Pos/Infra/Statistics/Statsd.hs|
|Reporting/Http.hs|RCustomReport|cardano-report-server/src/Pos/ReportServer/Report.hs|
|Recovery/Info.hs|SSInFuture|src/Pos/Infra/Recovery/Info.hs|
|Diffusion/Subscription/Dns.hs|DnsDomains |infra/src/Pos/Infra/Network/DnsDomains.hs|
|Diffusion/Types.hs|Diffusion m|infra/src/Pos/Infra/Diffusion/Types.hs|
|Network/Types.hs|NetworkConfig |infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|ShowableNetworkConfig |infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyCore|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyRelay|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyBehindNAT|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyP2P|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyTraditional|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|TopologyAuxx|infra/src/Pos/Infra/Network/Types.hs|
|Network/Types.hs|NetworkConfig|infra/src/Pos/Infra/Network/Types.hs|
|DHT/Workers.hs|KademliaDHTInstance |infra/src/Pos/Infra/DHT/Real/Types.hs|
|Network/Yaml.hs|KademliaParams |Same module|
|Network/Yaml.hs|KademliaAddress |Same module|
|Network/Yaml.hs|NodeMetadata|Same module|
|Network/Yaml.hs|StaticPolicies |Same module|
|Network/Yaml.hs|SendOrForward |Same module|
|Network/Yaml.hs|Dequeue |networking/src/Network/Broadcast/OutboundQueue.hs|
|Slotting/Impl/Util.hs|EpochSlottingData |core/src/Pos/Core/Slotting/Types.hs|
|DHT/Real/Real.hs|KademliaDHTInstance |infra/src/Pos/Infra/DHT/Real/Types.hs|
|DHT/Real/Real.hs|KademliaParams |src/Pos/Infra/Network/Yaml.hs|
|DHT/Real/Real.hs|Peer|kademlia|
|Network/CLI.hs|NetworkConfigOpts|dame module|
|Network/CLI.hs|TopologyCore |infra/src/Pos/Infra/Network/Types.hs|
|Network/CLI.hs|TopologyRelay |infra/src/Pos/Infra/Network/Types.hs|
|Network/CLI.hs|TopologyBehindNAT|infra/src/Pos/Infra/Network/Types.hs|
|Network/CLI.hs|TopologyP2P|infra/src/Pos/Infra/Network/Types.hs|
|Network/CLI.hs|TopologyTraditional|infra/src/Pos/Infra/Network/Types.hs|
|Slotting/Util.hs|SlotId |src/Pos/Core/Slotting/SlotId.hs|
|Communication/Types/Relay.hs|ResMsg |Same module|
|Communication/Relay/Logic.hs|DataMsg|infra/src/Pos/Infra/Communication/Types/Relay.hs|
|Communication/Relay/Logic.hs|InvReqDataParams|infra/src/Pos/Infra/Communication/Relay/Class.hs|
|Communication/Relay/Logic.hs|DataParams|infra/src/Pos/Infra/Communication/Relay/Class.hs|
|Communication/Relay/Logic.hs|InvMsg|infra/src/Pos/Infra/Communication/Types/Relay.hs|
|Communication/Types/Protocol.hs|VerInfo |Same module|

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