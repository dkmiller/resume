FROM mcr.microsoft.com/devcontainers/universal:2

USER codespace

# https://yihui.org/tinytex/#installation
RUN wget -qO- "https://yihui.org/tinytex/install-bin-unix.sh" | sh

RUN tlmgr install enumitem fancyhdr ragged2e xifthen ifmtarg setspace parskip setspace
