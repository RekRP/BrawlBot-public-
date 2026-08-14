FROM archlinux:base

RUN pacman -Syu --noconfirm && \
    pacman -S --noconfirm base-devel git curl zsh openssh python python-pip

RUN  pip install --break-system-packages discord

