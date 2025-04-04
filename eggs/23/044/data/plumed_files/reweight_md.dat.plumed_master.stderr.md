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
[fv-az805-507:05576] *** Process received signal ***
[fv-az805-507:05576] Signal: Aborted (6)
[fv-az805-507:05576] Signal code:  (-6)
[fv-az805-507:05576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc7dc45330]
[fv-az805-507:05576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc7dc9eb2c]
[fv-az805-507:05576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc7dc4527e]
[fv-az805-507:05576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc7dc288ff]
[fv-az805-507:05576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc7e0a5ff5]
[fv-az805-507:05576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc7e0bb0da]
[fv-az805-507:05576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc7e0a5a55]
[fv-az805-507:05576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc7e0a5a6f]
[fv-az805-507:05576] [ 8] plumed_master(+0x146dd)[0x560ff4bc86dd]
[fv-az805-507:05576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc7dc2a1ca]
[fv-az805-507:05576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc7dc2a28b]
[fv-az805-507:05576] [11] plumed_master(+0x15365)[0x560ff4bc9365]
[fv-az805-507:05576] *** End of error message ***
</pre>
{% endraw %}
