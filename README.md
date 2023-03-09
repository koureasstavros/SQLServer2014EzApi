# EzApi2014

Fork of [EzApi](http://sqlsrvintegrationsrv.codeplex.com/releases/view/21238) adapted for SQL Server 2014 version. Stand-alone edition forked by KoureasS & GitHub.

## Instructions
SQLServer2014EzApi is producing SQL Server Packages with the following charateristics:
1. Build --> 12
2. PackageFormatVersion --> 8
3. TargetSQLServerVersion --> 2014

*Based on Microsoft Intructions, SQLServerPackages should be deployed on SQLServer using aligned version of Management Studio.
**Management Studio deployment wizard may affect the Build and PackageFormatVersion in case of using a newer version of SSMS for deploying package with older TargetSQLServerVersion version.

## Updates
2023-03-09 Added EzExecutables.EzPackage.MaxConcurrentExecutables

## Changelog
Major changes from SQLServer2012EzApi --> SQLServer2014EzApi
1. EzComponents.EzComponent.SetOutputSorted
2. EzComponents.EzComponent.SetOutputColumnErrorRowDisposition
3. EzComponents.EzComponent.SetOutputColumnTruncationRowDisposition
4. EzComponents.EzComponent.UnmapColumn
5. EzComponents.EzComponent.UnmapAllInputColumns
6. EzComponents.EzOleDbAdapter.SQLCommandVariable
7. EzComponents.EzRowCount
8. EzComponents.EzDerivedColumn
9. EzConnections.EzConnectionManager.SetExpression
10. EzConnections.EzFlatFileCM.DefineColumnsInCM
11. EzExecutables.EzContainer.DelayValidation
12. EzExecutables.EzSequence.DtsProperties
13. EzExecutables.EzSequence.SetExpression
14. EzExecutables.OleDBDataTypes
15. EzExecutables.EzForEachLoop.ForEachVariableMappings
16. EzExecutables.EzPackage.Configurations
17. EzExecutables.EzPackage.EnableConfigurations
18. EzExecutables.EzPackage.DtsEventHandlers
19. EzExecutables.EzTask.SetExpression
20. EzExecutables.EzExpressionTask
21. EzExecutables.EzExecPackage.UseProjectReference
22. EzExecutables.EzExecPackage.IDTSParameterAssignments
23. EzExecutables.EzExecSqlTask.IsQueryStoredProcedure
24. EzExecutables.EzExecSqlTask.IDTSResultBindings

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Credits are for Microsoft =)

## License

The project inherits the Microsoft license: 

Copyright © Microsoft Corporation.  All Rights Reserved.

This code released under the terms of the 

Microsoft Public License (MS-PL, http://opensource.org/licenses/ms-pl.html.)
