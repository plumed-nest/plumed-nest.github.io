**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1910-428:63131] *** Process received signal ***
[fv-az1910-428:63131] Signal: Aborted (6)
[fv-az1910-428:63131] Signal code:  (-6)
[fv-az1910-428:63131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f321bc45330]
[fv-az1910-428:63131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f321bc9eb2c]
[fv-az1910-428:63131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f321bc4527e]
[fv-az1910-428:63131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f321bc288ff]
[fv-az1910-428:63131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f321c0a5ff5]
[fv-az1910-428:63131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f321c0bb0da]
[fv-az1910-428:63131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f321c0a5a55]
[fv-az1910-428:63131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f321c0a5a6f]
[fv-az1910-428:63131] [ 8] plumed_master(+0x146dd)[0x5563376bb6dd]
[fv-az1910-428:63131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f321bc2a1ca]
[fv-az1910-428:63131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f321bc2a28b]
[fv-az1910-428:63131] [11] plumed_master(+0x15365)[0x5563376bc365]
[fv-az1910-428:63131] *** End of error message ***
</pre>
{% endraw %}
