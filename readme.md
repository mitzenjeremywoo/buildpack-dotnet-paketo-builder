
## 

This builder for dotnet only work with dotnet core 6.0. 


## To build the image 

It is using builder paketo-buildpacks/dotnet-core.

You can find more details of the builder here via https://registry.buildpacks.io/searches/paketo


pack build my-app --buildpack paketo-buildpacks/dotnet-core --builder paketobuildpacks/builder-jammy-base

## To test out your image 
docker run --rm -p 8080:8080 my-app  

