**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az2233-502:65504] *** Process received signal ***
[fv-az2233-502:65504] Signal: Aborted (6)
[fv-az2233-502:65504] Signal code:  (-6)
[fv-az2233-502:65504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f70cca45330]
[fv-az2233-502:65504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f70cca9eb2c]
[fv-az2233-502:65504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f70cca4527e]
[fv-az2233-502:65504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f70cca288ff]
[fv-az2233-502:65504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f70ccea5ff5]
[fv-az2233-502:65504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f70ccebb0da]
[fv-az2233-502:65504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f70ccea5a55]
[fv-az2233-502:65504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f70ccea5a6f]
[fv-az2233-502:65504] [ 8] plumed_master(+0x146dd)[0x5637472966dd]
[fv-az2233-502:65504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f70cca2a1ca]
[fv-az2233-502:65504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f70cca2a28b]
[fv-az2233-502:65504] [11] plumed_master(+0x15365)[0x563747297365]
[fv-az2233-502:65504] *** End of error message ***
</pre>
{% endraw %}
