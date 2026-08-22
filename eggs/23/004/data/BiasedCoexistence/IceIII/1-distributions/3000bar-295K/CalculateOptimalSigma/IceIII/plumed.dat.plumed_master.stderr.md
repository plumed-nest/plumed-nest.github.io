**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervm76f27:06142] *** Process received signal ***
[runnervm76f27:06142] Signal: Aborted (6)
[runnervm76f27:06142] Signal code:  (-6)
[runnervm76f27:06142] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f372c045330]
[runnervm76f27:06142] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f372c09ec0c]
[runnervm76f27:06142] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f372c04527e]
[runnervm76f27:06142] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f372c0288ff]
[runnervm76f27:06142] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f372c4a5ff5]
[runnervm76f27:06142] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f372c4bb0da]
[runnervm76f27:06142] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f372c4a5a55]
[runnervm76f27:06142] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f372c4a5a6f]
[runnervm76f27:06142] [ 8] plumed_master(+0x146dd)[0x5649986346dd]
[runnervm76f27:06142] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f372c02a1ca]
[runnervm76f27:06142] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f372c02a28b]
[runnervm76f27:06142] [11] plumed_master(+0x15365)[0x564998635365]
[runnervm76f27:06142] *** End of error message ***
</pre>
{% endraw %}
