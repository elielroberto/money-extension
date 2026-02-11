O MoneyExtension é uma pequena biblioteca em C# criada para facilitar a conversão de valores do tipo decimal para int no formato de centavos.

O objetivo do projeto foi publicar um pacote simples e reutilizável no NuGet, ajudando a padronizar operações financeiras em aplicações .NET.

 Instalação via NuGet
 
 dotnet add package MoneyExtensionsEliel

 Install-Package MoneyExtensionEliel

 using MoneyExtensionEliel;

decimal valor = 279.98M;
int cents = valor.ToCents();

// Resultado: 27998
