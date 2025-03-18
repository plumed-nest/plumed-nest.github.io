**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp450K/Distribution/plumed.dat   
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
[fv-az1267-279:66004] *** Process received signal ***
[fv-az1267-279:66004] Signal: Aborted (6)
[fv-az1267-279:66004] Signal code:  (-6)
[fv-az1267-279:66004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f629d645330]
[fv-az1267-279:66004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f629d69eb2c]
[fv-az1267-279:66004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f629d64527e]
[fv-az1267-279:66004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f629d6288ff]
[fv-az1267-279:66004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f629daa5ff5]
[fv-az1267-279:66004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f629dabb0da]
[fv-az1267-279:66004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f629daa5a55]
[fv-az1267-279:66004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f629daa5a6f]
[fv-az1267-279:66004] [ 8] plumed_master(+0x146dd)[0x55d1772cb6dd]
[fv-az1267-279:66004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f629d62a1ca]
[fv-az1267-279:66004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f629d62a28b]
[fv-az1267-279:66004] [11] plumed_master(+0x15365)[0x55d1772cc365]
[fv-az1267-279:66004] *** End of error message ***
</pre>
{% endraw %}
