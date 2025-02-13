**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1390-170:09615] *** Process received signal ***
[fv-az1390-170:09615] Signal: Aborted (6)
[fv-az1390-170:09615] Signal code:  (-6)
[fv-az1390-170:09615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30fbc45330]
[fv-az1390-170:09615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30fbc9eb2c]
[fv-az1390-170:09615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30fbc4527e]
[fv-az1390-170:09615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30fbc288ff]
[fv-az1390-170:09615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30fc0a5ff5]
[fv-az1390-170:09615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30fc0bb0da]
[fv-az1390-170:09615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30fc0a5a55]
[fv-az1390-170:09615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30fc0a5a6f]
[fv-az1390-170:09615] [ 8] plumed_master(+0x146dd)[0x5571cf3046dd]
[fv-az1390-170:09615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30fbc2a1ca]
[fv-az1390-170:09615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30fbc2a28b]
[fv-az1390-170:09615] [11] plumed_master(+0x15365)[0x5571cf305365]
[fv-az1390-170:09615] *** End of error message ***
</pre>
{% endraw %}
