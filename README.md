# sbqhq
blank fans for qhq 

## windows

please install a virtul machine to run macOS or Linux

## macOS

first you should enter your work space.

Then you should modify ``qaq.sh``at line2, replace ``/usr/local/bashProject``of your workspace.

then run ``sh qaq.sh`` to test if your terminal can load *.jpg or *.png.

if there are errors about ``imgcat``, then you should run ``brew install iterm2``&``brew install eddieantonio/eddieantonio/imgcat``,and run ``sh qaq.sh``in your iterm.

if you want to use alias anywhere, just modify your ``~/.zshrc``or ``~/.bash_profile``, and add ``export PATH=yourPATH:$PATH ``, then add ``alias yourname='sh qaq.sh'``after this. Then you can run ``yourname``in terminal to show these nauseated things about qhq.



## Ubuntu Linux

first you should check if you have imgcat, if not you should run ``sudo snap install imgcat``.

Then you should modify ``qaq.sh``at line2, replace ``/usr/local/bashProject``of your workspace.

then you should run ``g++ qaq.cpp -o qaq``to create the executable program.

Now you can run ``sh qaq.sh`` to see the result.

If you want to use alias out of workspace, just modify your ``~/.bashrc``, and add ``export PATH=$PATH：yourPATH ``, then add ``alias yourname='sh qaq.sh'``after this.







