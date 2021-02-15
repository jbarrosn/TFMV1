Para instalar el paquete de la transformada de Fourier rápida FFTW3 en Ubuntu o en una distribucion de Linux, hay que correr en la terminal:

sudo apt install libfftw3-bin libfftw3-dev libfftw3-doc

Para instalar las dependencias de pyhon necesarias:

pip install -r pip_requirements.txt

Para correr la simulación en 1D:

make

Los archivos para 2D y 3D se encuentran en la carpeta Legacy.

Para correr en dichas dimensiones:

sh 2Drun.sh
sh 3Drun.sh
