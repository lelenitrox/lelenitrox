[19:04:40.810] Using game files from: C:\Users\lele\Desktop\Subnautica.v67813
[19:04:41.230] Value does not fall within the expected range.
Press L to open log file before closing. Press any other key to close . . .
System.ArgumentException: Value does not fall within the expected range.
   at NitroxServer_Subnautica.Serialization.Resources.ResourceAssets.ValidateMembers()
   at NitroxServer_Subnautica.Serialization.Resources.ResourceAssetsParser.Parse()
   at NitroxServer_Subnautica.SubnauticaServerAutoFacRegistrar.RegisterDependencies(ContainerBuilder containerBuilder)
   at NitroxModel.Core.NitroxServiceLocator.InitializeDependencyContainer(IAutoFacRegistrar[] registrars) in C:\Users\Sunrunner\Desktop\Code\Nitrox\NitroxModel\Core\NitroxServiceLocator.cs:line 16
   at NitroxServer_Subnautica.Program.<Main>d__3.MoveNext()
--- End of stack trace from previous location where exception was thrown ---
   at System.Runtime.CompilerServices.TaskAwaiter.ThrowForNonSuccess(Task task)
   at System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   at NitroxServer_Subnautica.Program.<Main>(String[] args)
