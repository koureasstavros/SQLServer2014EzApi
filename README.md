# EzApi2014

Fork of [EzApi](http://sqlsrvintegrationsrv.codeplex.com/releases/view/21238) adapted for SQL Server 2014 version. Stand-alone edition forked by KoureasS & GitHub.

## Instructions
SQLServer2014EzApi is producing SQL Server Packages with the following charateristics:
1. Build --> 12
2. PackageFormatVersion --> 8
3. TargetSQLServerVersion --> 2014

*Based on Microsoft Intructions, SQLServerPackages should be deployed on SQLServer using aligned version of Management Studio.
**Management Studio deployment wizard may affect the Build and PackageFormatVersion in case of using a newer version of SSMS for deploying package with older TargetSQLServerVersion version.

##Changelog
Major changes from SQLServer2012EzApi --> SQLServer2014EzApi
+EzComponents.EzComponent.SetOutputSorted
+EzComponents.EzComponent.SetOutputColumnErrorRowDisposition
+EzComponents.EzComponent.SetOutputColumnTruncationRowDisposition
+EzComponents.EzComponent.UnmapColumn
+EzComponents.EzComponent.UnmapAllInputColumns
+EzComponents.EzOleDbAdapter.SQLCommandVariable
+EzComponents.EzRowCount
+EzComponents.EzDerivedColumn
+EzConnections.EzConnectionManager.SetExpression
+EzConnections.EzFlatFileCM.DefineColumnsInCM
+EzExecutables.EzContainer.DelayValidation
+EzExecutables.EzSequence.DtsProperties
+EzExecutables.EzSequence.SetExpression
+EzExecutables.OleDBDataTypes
+EzExecutables.EzForEachLoop.ForEachVariableMappings
+EzExecutables.EzPackage.Configurations
+EzExecutables.EzPackage.EnableConfigurations
+EzExecutables.EzPackage.DtsEventHandlers
+EzExecutables.EzTask.SetExpression
+EzExecutables.EzExpressionTask
+EzExecutables.EzExecPackage.UseProjectReference
+EzExecutables.EzExecPackage.IDTSParameterAssignments
+EzExecutables.EzExecSqlTask.IsQueryStoredProcedure
+EzExecutables.EzExecSqlTask.IDTSResultBindings

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
