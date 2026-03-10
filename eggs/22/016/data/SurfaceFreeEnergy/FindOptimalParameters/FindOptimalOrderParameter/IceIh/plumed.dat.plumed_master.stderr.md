**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervm0kj6c:06861] *** Process received signal ***
[runnervm0kj6c:06861] Signal: Aborted (6)
[runnervm0kj6c:06861] Signal code:  (-6)
[runnervm0kj6c:06861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4f9245330]
[runnervm0kj6c:06861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4f929eb2c]
[runnervm0kj6c:06861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4f924527e]
[runnervm0kj6c:06861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4f92288ff]
[runnervm0kj6c:06861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4f96a5ff5]
[runnervm0kj6c:06861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4f96bb0da]
[runnervm0kj6c:06861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4f96a5a55]
[runnervm0kj6c:06861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4f96a5a6f]
[runnervm0kj6c:06861] [ 8] plumed_master(+0x146dd)[0x55f3585a76dd]
[runnervm0kj6c:06861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4f922a1ca]
[runnervm0kj6c:06861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4f922a28b]
[runnervm0kj6c:06861] [11] plumed_master(+0x15365)[0x55f3585a8365]
[runnervm0kj6c:06861] *** End of error message ***
</pre>
{% endraw %}
