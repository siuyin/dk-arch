A basic archlinux container with go installed.
To run as unpriviledged user 'siuyin'

docker run --name arch -it -v $(pwd):/h -h arch --user siuyin siuyin/arch
