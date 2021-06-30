# labview-grpc-client-using-CSharp
A LabVIEW gRPC Client using C# Example

# Creating gRPC C# Client DLL
Open the C# Client folder in VS Code and follow the onscreen prompts to install the dependencies. 
Do a release build by using the below command in terminal:
dotnet build -c release

# Running the Server
The gRPC server code is same as the one created by NI at https://github.com/ni/grpc-labview
To run the server, run the Main.vi located at 
Server\Servers\Query Server\Query Server Class\Main.vi

# Running the LabVIEW gRPC Client
Ensure that you have built the C# gRPC DLL before trying this.
Run the example gRPC LabVIEW Client example located at
Client\Example gRPC Client Call.vi
