**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[fv-az2233-502:61885] *** Process received signal ***
[fv-az2233-502:61885] Signal: Aborted (6)
[fv-az2233-502:61885] Signal code:  (-6)
[fv-az2233-502:61885] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee0d445330]
[fv-az2233-502:61885] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee0d49eb2c]
[fv-az2233-502:61885] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee0d44527e]
[fv-az2233-502:61885] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee0d4288ff]
[fv-az2233-502:61885] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee0d8a5ff5]
[fv-az2233-502:61885] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee0d8bb0da]
[fv-az2233-502:61885] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee0d8a5a55]
[fv-az2233-502:61885] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee0d8a5a6f]
[fv-az2233-502:61885] [ 8] plumed_master(+0x146dd)[0x5651245796dd]
[fv-az2233-502:61885] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee0d42a1ca]
[fv-az2233-502:61885] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee0d42a28b]
[fv-az2233-502:61885] [11] plumed_master(+0x15365)[0x56512457a365]
[fv-az2233-502:61885] *** End of error message ***
</pre>
{% endraw %}
