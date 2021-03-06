# libSyntax nodes status

## Expression

### Done:
  * NilLiteralExpr
  * IntegerLiteralExpr
  * FloatLiteralExpr
  * BooleanLiteralExpr
  * StringLiteralExpr
  * DiscardAssignmentExpr
  * DeclRefExpr
  * IfExpr
  * AssignExpr
  * TypeExpr
  * UnresolvedMemberExpr
  * SequenceExpr
  * TupleElementExpr
  * TupleExpr
  * ArrayExpr
  * DictionaryExpr
  * PrefixUnaryExpr
  * TryExpr
  * ForceTryExpr
  * OptionalTryExpr
  * ClosureExpr
  * FunctionCallExpr
  * SubscriptExpr
  * DotSelfExpr
  * PostfixUnaryExpr
  * ForcedValueExpr
  * SuperRefExpr
  * ImplicitMemberExpr
  * InterpolatedStringLiteralExpr
  * KeyPathExpr
  * KeyPathDotExpr
  * InOutExpr
  * EditorPlaceholderExpr
  * ObjectLiteralExpr
  * MagicIdentifierLiteralExpr
  * SpecializeExpr
  * UnresolvedPatternExpr
  * IsExpr
  * AsExpr
  * ArrowExpr

### Not-started (UnknownExpr):
  * ObjCSelectorExpr

## Declaration

### Done:
  * TopLevelCodeDecl
  * ClassDecl
  * StructDecl
  * FuncDecl
  * ProtocolDecl
  * ImportDecl
  * AssociatedTypeDecl
  * TypeAliasDecl
  * IfConfigDecl
  * PatternBindingDecl
  * VarDecl
  * ExtensionDecl
  * SubscriptDecl
  * ConstructorDecl
  * DestructorDecl
  * EnumDecl
  * EnumCaseDecl
  * PrecedenceGroupDecl

### Not-started (UnknownDecl):
  * InfixOperatorDecl
  * PrefixOperatorDecl
  * PostfixOperatorDecl

## Statement
### Done:
  * BraceStmt
  * ReturnStmt
  * DeferStmt
  * DoStmt
  * RepeatWhileStmt
  * BreakStmt
  * ContinueStmt
  * FallthroughStmt
  * ThrowStmt
  * IfStmt
  * GuardStmt
  * WhileStmt
  * ForInStmt
  * SwitchStmt

## Pattern
### Done:
  * IdentifierPattern
  * WildcardPattern
  * TuplePattern
  * ExpressionPattern
  * ValueBindingPattern
  * IsTypePattern

### Not-started:
  * AsTypePattern
  * OptionalPattern
  * EnumCasePattern

## TypeRepr
### Done:
  * SimpleTypeIdentifier
  * MemberTypeIdentifier
  * ArrayType
  * DictionaryType
  * MetatypeType
  * OptionalType
  * ImplicitlyUnwrappedOptionalType
  * CompositionType
  * TupleType
  * FunctionType
  * AttributedType
