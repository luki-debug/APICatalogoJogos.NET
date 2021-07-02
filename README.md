# :video_game: Api Catalogo de Jogos :video_game:
Api RestFull de catálogo de jogos utilizando boas praticas de arquitetura com .NET.

Os objetos para consulta e inserção estão configurados para armazenar em memoria mas o projeto pode ser configurado para armazenar em um banco de dados SqlServer ou acrescentar o driver de outro SGBD.

A configuração para apontar ao banco deve ser alterada na StartUp em: services.AddScoped<IJogoRepository, JogoRepository>();