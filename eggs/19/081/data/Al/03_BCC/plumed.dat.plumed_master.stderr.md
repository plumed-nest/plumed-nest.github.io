**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.QFv1Tn.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
Compiler search PATH: /home/runner/opt/bin:/opt/hostedtoolcache/Python/3.10.22/x64/bin:/opt/hostedtoolcache/Python/3.10.22/x64:/snap/bin:/home/runner/.local/bin:/opt/pipx_bin:/home/runner/.cargo/bin:/home/runner/.config/composer/vendor/bin:/usr/local/.ghcup/bin:/home/runner/.dotnet/tools:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
ERROR : in input for command line tool driver :
(core/PlumedMain.cpp:1997) void PLMD::PlumedMain::load(const std::string&, const std::vector<std::__cxx11::basic_string<char> >&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' '/home/runner/opt/lib/plumed_master/scripts/mklib.sh' '-n' '-o' './../../RefCV.2.11.0-dev.490f6939c0ef76c8ab93abd1cdccc82d7de616e0bc89ad67c32a56c3af2f3869.so' '../../RefCV.cpp'

</pre>
{% endraw %}
