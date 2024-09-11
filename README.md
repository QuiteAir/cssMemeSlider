# cssMemeSlider

https://QuiteAir.github.io/cssMemeSlider/cssMemeSlider/

## PowerShell commit setup

git commit --amend -m "init: start cssMemeSlider-task ($(Get-Date -Format 'ddd, MMM dd, yyyy hh:mm:ss tt'))"

###

To temparly set the lacale for the current session to use getDate

[System.Threading.Thread]::CurrentThread.CurrentCulture = [System.Globalization.CultureInfo]::GetCultureInfo("en-US")

[System.Threading.Thread]::CurrentThread.CurrentUICulture = [System.Globalization.CultureInfo]::GetCultureInfo("en-US")
