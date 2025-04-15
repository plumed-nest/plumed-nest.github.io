**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az2233-502:61199] *** Process received signal ***
[fv-az2233-502:61199] Signal: Aborted (6)
[fv-az2233-502:61199] Signal code:  (-6)
[fv-az2233-502:61199] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8505045330]
[fv-az2233-502:61199] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f850509eb2c]
[fv-az2233-502:61199] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f850504527e]
[fv-az2233-502:61199] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85050288ff]
[fv-az2233-502:61199] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85054a5ff5]
[fv-az2233-502:61199] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85054bb0da]
[fv-az2233-502:61199] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85054a5a55]
[fv-az2233-502:61199] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85054a5a6f]
[fv-az2233-502:61199] [ 8] plumed_master(+0x146dd)[0x55819ae856dd]
[fv-az2233-502:61199] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f850502a1ca]
[fv-az2233-502:61199] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f850502a28b]
[fv-az2233-502:61199] [11] plumed_master(+0x15365)[0x55819ae86365]
[fv-az2233-502:61199] *** End of error message ***
</pre>
{% endraw %}
