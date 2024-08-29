Configuration MyWebServer {
    Import-DscResource -ModuleName 'PSDesiredStateConfiguration'
    Node localhost {
        WindowsFeature IIS {
            Ensure = "Present"
            Name   = "MyWebServer"
        }
    }
}

Write-Host "MyWebServer configuration has been loaded."
