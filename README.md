# projeto-sistema-web
Uniftec - Disciplina Projeto de Sistemas para Web

# ASP.NET Core Docker

```
git clone https://github.com/rbarros/projeto-sistema-web.git
cd projeto-sistema-web
docker build -t aspnetapp .
docker run -p 8000:80 -e "ASPNETCORE_URLS=http://+:80" -it --rm --name Ftec.Cadastro.Site aspnetapp
```

Depois da aplicação iniciar, visite `http://localhost:8000` no seu navegador.
