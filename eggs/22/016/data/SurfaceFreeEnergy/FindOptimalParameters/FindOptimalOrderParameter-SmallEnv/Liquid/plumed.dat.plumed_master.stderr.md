**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1278-681:62889] *** Process received signal ***
[fv-az1278-681:62889] Signal: Aborted (6)
[fv-az1278-681:62889] Signal code:  (-6)
[fv-az1278-681:62889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb216845330]
[fv-az1278-681:62889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21689eb2c]
[fv-az1278-681:62889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21684527e]
[fv-az1278-681:62889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2168288ff]
[fv-az1278-681:62889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb216ca5ff5]
[fv-az1278-681:62889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb216cbb0da]
[fv-az1278-681:62889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb216ca5a55]
[fv-az1278-681:62889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb216ca5a6f]
[fv-az1278-681:62889] [ 8] plumed_master(+0x146dd)[0x55a38a02f6dd]
[fv-az1278-681:62889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21682a1ca]
[fv-az1278-681:62889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21682a28b]
[fv-az1278-681:62889] [11] plumed_master(+0x15365)[0x55a38a030365]
[fv-az1278-681:62889] *** End of error message ***
</pre>
{% endraw %}
