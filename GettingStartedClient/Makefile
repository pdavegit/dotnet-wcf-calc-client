all:
	dotnet publish -c Release
	docker build -t prashantdave/dotnet-wcf-calc-client:latest -f Dockerfile .
	docker push prashantdave/dotnet-wcf-calc-client:latest
