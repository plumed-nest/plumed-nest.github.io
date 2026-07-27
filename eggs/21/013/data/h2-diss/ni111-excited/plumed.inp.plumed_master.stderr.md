**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zGq4o9/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmvrwv9:08144] *** Process received signal ***
[runnervmvrwv9:08144] Signal: Aborted (6)
[runnervmvrwv9:08144] Signal code:  (-6)
[runnervmvrwv9:08144] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb2ed845330]
[runnervmvrwv9:08144] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb2ed89eb2c]
[runnervmvrwv9:08144] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb2ed84527e]
[runnervmvrwv9:08144] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2ed8288ff]
[runnervmvrwv9:08144] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2edca5ff5]
[runnervmvrwv9:08144] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2edcbb0da]
[runnervmvrwv9:08144] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2edca5a55]
[runnervmvrwv9:08144] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2edca5a6f]
[runnervmvrwv9:08144] [ 8] plumed_master(+0x146dd)[0x55a59525f6dd]
[runnervmvrwv9:08144] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb2ed82a1ca]
[runnervmvrwv9:08144] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb2ed82a28b]
[runnervmvrwv9:08144] [11] plumed_master(+0x15365)[0x55a595260365]
[runnervmvrwv9:08144] *** End of error message ***
</pre>
{% endraw %}
