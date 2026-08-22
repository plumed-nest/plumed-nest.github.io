**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervm76f27:07011] *** Process received signal ***
[runnervm76f27:07011] Signal: Aborted (6)
[runnervm76f27:07011] Signal code:  (-6)
[runnervm76f27:07011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc80c245330]
[runnervm76f27:07011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc80c29ec0c]
[runnervm76f27:07011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc80c24527e]
[runnervm76f27:07011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc80c2288ff]
[runnervm76f27:07011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc80c6a5ff5]
[runnervm76f27:07011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc80c6bb0da]
[runnervm76f27:07011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc80c6a5a55]
[runnervm76f27:07011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc80c6a5a6f]
[runnervm76f27:07011] [ 8] plumed_master(+0x146dd)[0x55dc21bd36dd]
[runnervm76f27:07011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc80c22a1ca]
[runnervm76f27:07011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc80c22a28b]
[runnervm76f27:07011] [11] plumed_master(+0x15365)[0x55dc21bd4365]
[runnervm76f27:07011] *** End of error message ***
</pre>
{% endraw %}
