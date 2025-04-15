**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp600K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[fv-az1047-397:67134] *** Process received signal ***
[fv-az1047-397:67134] Signal: Aborted (6)
[fv-az1047-397:67134] Signal code:  (-6)
[fv-az1047-397:67134] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45db245330]
[fv-az1047-397:67134] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45db29eb2c]
[fv-az1047-397:67134] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45db24527e]
[fv-az1047-397:67134] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45db2288ff]
[fv-az1047-397:67134] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45db6a5ff5]
[fv-az1047-397:67134] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45db6bb0da]
[fv-az1047-397:67134] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45db6a5a55]
[fv-az1047-397:67134] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45db6a5a6f]
[fv-az1047-397:67134] [ 8] plumed_master(+0x146dd)[0x5569cb8fd6dd]
[fv-az1047-397:67134] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45db22a1ca]
[fv-az1047-397:67134] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45db22a28b]
[fv-az1047-397:67134] [11] plumed_master(+0x15365)[0x5569cb8fe365]
[fv-az1047-397:67134] *** End of error message ***
</pre>
{% endraw %}
