FROM jenkins/jenkins
USER root

RUN wget -q http://ftp.us.debian.org/debian/pool/main/libu/liburcu/liburcu2_0.8.5-1_amd64.deb && \
wget -q http://launchpadlibrarian.net/228187061/liblttng-ust-ctl2_2.7.1-1_amd64.deb && \
wget -q http://mirrors.kernel.org/ubuntu/pool/universe/u/ust/liblttng-ust0_2.7.1-1_amd64.deb && \
wget -q http://mirrors.kernel.org/ubuntu/pool/universe/libu/liburcu/liburcu4_0.9.1-3_amd64.deb && \
wget -q http://security.ubuntu.com/ubuntu/pool/main/o/openssl1.0/libssl1.0.0_1.0.2n-1ubuntu5.3_amd64.deb && \
wget -q http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu60_60.2-3ubuntu3.1_amd64.deb && \
dpkg -i liburcu4_0.9.1-3_amd64.deb && \
dpkg -i liblttng-ust-ctl2_2.7.1-1_amd64.deb && \
dpkg -i liblttng-ust0_2.7.1-1_amd64.deb && \
dpkg -i liburcu2_0.8.5-1_amd64.deb && \
dpkg -i libssl1.0.0_1.0.2n-1ubuntu5.3_amd64.deb && \
dpkg -i libicu60_60.2-3ubuntu3.1_amd64.deb && \
wget -q https://github.com/PowerShell/PowerShell/releases/download/v7.0.0/powershell-lts_7.0.0-1.ubuntu.18.04_amd64.deb && \
dpkg -i powershell-lts_7.0.0-1.ubuntu.18.04_amd64.deb
