**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1278-681:62618] *** Process received signal ***
[fv-az1278-681:62618] Signal: Aborted (6)
[fv-az1278-681:62618] Signal code:  (-6)
[fv-az1278-681:62618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4d6045330]
[fv-az1278-681:62618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4d609eb2c]
[fv-az1278-681:62618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4d604527e]
[fv-az1278-681:62618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4d60288ff]
[fv-az1278-681:62618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4d64a5ff5]
[fv-az1278-681:62618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4d64bb0da]
[fv-az1278-681:62618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4d64a5a55]
[fv-az1278-681:62618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4d64a5a6f]
[fv-az1278-681:62618] [ 8] plumed_master(+0x146dd)[0x563e4e3766dd]
[fv-az1278-681:62618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4d602a1ca]
[fv-az1278-681:62618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4d602a28b]
[fv-az1278-681:62618] [11] plumed_master(+0x15365)[0x563e4e377365]
[fv-az1278-681:62618] *** End of error message ***
</pre>
{% endraw %}
