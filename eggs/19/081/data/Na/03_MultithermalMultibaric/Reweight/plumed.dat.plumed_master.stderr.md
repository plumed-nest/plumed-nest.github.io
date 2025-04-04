**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az805-507:10312] *** Process received signal ***
[fv-az805-507:10312] Signal: Aborted (6)
[fv-az805-507:10312] Signal code:  (-6)
[fv-az805-507:10312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3922c45330]
[fv-az805-507:10312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3922c9eb2c]
[fv-az805-507:10312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3922c4527e]
[fv-az805-507:10312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3922c288ff]
[fv-az805-507:10312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39230a5ff5]
[fv-az805-507:10312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39230bb0da]
[fv-az805-507:10312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39230a5a55]
[fv-az805-507:10312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39230a5a6f]
[fv-az805-507:10312] [ 8] plumed_master(+0x146dd)[0x56294f4746dd]
[fv-az805-507:10312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3922c2a1ca]
[fv-az805-507:10312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3922c2a28b]
[fv-az805-507:10312] [11] plumed_master(+0x15365)[0x56294f475365]
[fv-az805-507:10312] *** End of error message ***
</pre>
{% endraw %}
