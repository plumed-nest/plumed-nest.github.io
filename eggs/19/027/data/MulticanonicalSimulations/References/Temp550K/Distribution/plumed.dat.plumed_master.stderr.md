**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp550K/Distribution/plumed.dat   
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
[fv-az1374-933:13824] *** Process received signal ***
[fv-az1374-933:13824] Signal: Aborted (6)
[fv-az1374-933:13824] Signal code:  (-6)
[fv-az1374-933:13824] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1316245330]
[fv-az1374-933:13824] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f131629eb2c]
[fv-az1374-933:13824] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f131624527e]
[fv-az1374-933:13824] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13162288ff]
[fv-az1374-933:13824] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13166a5ff5]
[fv-az1374-933:13824] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13166bb0da]
[fv-az1374-933:13824] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13166a5a55]
[fv-az1374-933:13824] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13166a5a6f]
[fv-az1374-933:13824] [ 8] plumed_master(+0x146dd)[0x55b6fe62c6dd]
[fv-az1374-933:13824] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f131622a1ca]
[fv-az1374-933:13824] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f131622a28b]
[fv-az1374-933:13824] [11] plumed_master(+0x15365)[0x55b6fe62d365]
[fv-az1374-933:13824] *** End of error message ***
</pre>
{% endraw %}
