[Net.ServicePointManager]::SecurityProtocol = 'Tls12'
$p = Join-Path $env:TEMP 'ChromeStandaloneSetup64.exe'
Invoke-WebRequest 'https://dl.google.com/chrome/install/ChromeStandaloneSetup64.exe' -OutFile $p -UseBasicParsing
Start-Process $p -ArgumentList '/silent', '/install' -Wait
