**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
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
[fv-az1267-279:65938] *** Process received signal ***
[fv-az1267-279:65938] Signal: Aborted (6)
[fv-az1267-279:65938] Signal code:  (-6)
[fv-az1267-279:65938] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbabc45330]
[fv-az1267-279:65938] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbabc9eb2c]
[fv-az1267-279:65938] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbabc4527e]
[fv-az1267-279:65938] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbabc288ff]
[fv-az1267-279:65938] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbac0a5ff5]
[fv-az1267-279:65938] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbac0bb0da]
[fv-az1267-279:65938] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbac0a5a55]
[fv-az1267-279:65938] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbac0a5a6f]
[fv-az1267-279:65938] [ 8] plumed_master(+0x146dd)[0x561d120606dd]
[fv-az1267-279:65938] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbabc2a1ca]
[fv-az1267-279:65938] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbabc2a28b]
[fv-az1267-279:65938] [11] plumed_master(+0x15365)[0x561d12061365]
[fv-az1267-279:65938] *** End of error message ***
</pre>
{% endraw %}
