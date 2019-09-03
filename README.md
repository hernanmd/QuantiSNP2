# QuantiSNP2

```bash
apt-get update
apt-get install bc wget mlocate unzip nano
cd /opt
wget ftp://ftp.stats.ox.ac.uk/pub/yau/quantisnp2/mcr/MCRinstaller64.run
chmod 755 MCRinstaller64.run
./MCRinstaller64.run  --noexec --keep --nox11 --target Install
cd Install
./MCRInstaller.bin -is:extract
cd istemp<tab>
chmod 755 jre1.5.0-linux-amd64.bin
./jre1.5.0-linux-amd64.bin
./bin/java -jar setup.jar -console
cd ../..
wget ftp://ftp.stats.ox.ac.uk/pub/yau/quantisnp2/executables/09042010/install_quantisnp
chmod 755 install_quantisnp
./install_quantisnp
wget ftp://ftp.stats.ox.ac.uk/pub/yau/quantisnp2/download/b37.tar.gz
cd quantisnp/examples
```
