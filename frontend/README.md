docker build -t reactrouter_nestedroutes .

reactrouter_nestedroutes

docker run --rm -d --name reactrouter_nestedroutes -p 80:5173 reactrouter_nestedroutes

docker run --rm -d --name reactrouter_nestedroutes -p 5173:5173 reactrouter_nestedroutes
