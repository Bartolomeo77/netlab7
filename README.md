# netlab7


docker build -t aspnetapp -f Dockerfile .


docker run -it --rm -p 5000:80 --name aspnetcore_sample aspnetapp



http://localhost:5000/weatherforecast 
