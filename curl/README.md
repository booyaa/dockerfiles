# curl

# why?

curl v7.43 hasn't dropped in every distro or package manager. it's got some really cool features that you might want to try out.

# usage

do cool things like talk to docker via it's unix socket

    docker run -it --rm -v /var/run/docker.sock:/var/run/docker.sock booyaa/curl curl --unix-socket /var/run/docker.sock http://localhost/info

# bugs or feedback?

raise an issue through this [link](https://github.com/booyaa/dockerfiles/issues/new)

# thanks

- Nathan LeClaire for inspiring me to do this after seeing a stackoverflow post
- Jessie Frazelle for enlightening me about containerizing your apps (and the hint for linking unix sockets)
