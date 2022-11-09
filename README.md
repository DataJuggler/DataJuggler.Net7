# DataJuggler.Net
Update 10.19.2022: I updated Microsoft.Data.SqlClient to version 5.1.x, so I will likely have to include code
to fix connection strings broken by the 4.0.0 SqlClient. Haven't tested this part yet.'

Update 12.31.2021: This project has to be downgraded to Microsoft.Data.SqlClient 3.0.1, because of the (unwanted)
breaking changes in 4.0.0, which forces you install a certification in SQL Server, or put encrypt=false.

Updating Microsoft.Data.SqlClient is not recommended at this time.

DataJuggler.Net7 is a core component of several Data Juggler projects including DataTier.Net, DB Compare and XML Mirror.

Another project that uses CSharpClassWriter is called DataJuggler.Excelerate
https://github.com/DataJuggler/Excelerate


