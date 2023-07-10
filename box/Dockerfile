FROM fedora:latest

RUN dnf update -y &&\
    dnf install -y @core @standard fish git micro entr fzf kernel-tools moreutils openssl tmux screen waypipe wl-clipboard nmap pv &&\
    chsh --shell /usr/bin/fish

ENV EDITOR=micro

CMD ["/usr/bin/fish"]
