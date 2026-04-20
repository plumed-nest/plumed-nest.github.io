**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmeorf1:07365] *** Process received signal ***
[runnervmeorf1:07365] Signal: Aborted (6)
[runnervmeorf1:07365] Signal code:  (-6)
[runnervmeorf1:07365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfcfa45330]
[runnervmeorf1:07365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfcfa9eb2c]
[runnervmeorf1:07365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfcfa4527e]
[runnervmeorf1:07365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfcfa288ff]
[runnervmeorf1:07365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfcfea5ff5]
[runnervmeorf1:07365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfcfebb0da]
[runnervmeorf1:07365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfcfea5a55]
[runnervmeorf1:07365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfcfea5a6f]
[runnervmeorf1:07365] [ 8] plumed_master(+0x146dd)[0x56041640e6dd]
[runnervmeorf1:07365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfcfa2a1ca]
[runnervmeorf1:07365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfcfa2a28b]
[runnervmeorf1:07365] [11] plumed_master(+0x15365)[0x56041640f365]
[runnervmeorf1:07365] *** End of error message ***
</pre>
{% endraw %}
