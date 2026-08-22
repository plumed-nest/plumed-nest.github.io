**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervm76f27:06181] *** Process received signal ***
[runnervm76f27:06181] Signal: Aborted (6)
[runnervm76f27:06181] Signal code:  (-6)
[runnervm76f27:06181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f784f845330]
[runnervm76f27:06181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f784f89ec0c]
[runnervm76f27:06181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f784f84527e]
[runnervm76f27:06181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f784f8288ff]
[runnervm76f27:06181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f784fca5ff5]
[runnervm76f27:06181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f784fcbb0da]
[runnervm76f27:06181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f784fca5a55]
[runnervm76f27:06181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f784fca5a6f]
[runnervm76f27:06181] [ 8] plumed_master(+0x146dd)[0x564e0d2516dd]
[runnervm76f27:06181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f784f82a1ca]
[runnervm76f27:06181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f784f82a28b]
[runnervm76f27:06181] [11] plumed_master(+0x15365)[0x564e0d252365]
[runnervm76f27:06181] *** End of error message ***
</pre>
{% endraw %}
