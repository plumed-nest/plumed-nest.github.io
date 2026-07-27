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
[runnervmvrwv9:06678] *** Process received signal ***
[runnervmvrwv9:06678] Signal: Aborted (6)
[runnervmvrwv9:06678] Signal code:  (-6)
[runnervmvrwv9:06678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe3d845330]
[runnervmvrwv9:06678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe3d89eb2c]
[runnervmvrwv9:06678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe3d84527e]
[runnervmvrwv9:06678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe3d8288ff]
[runnervmvrwv9:06678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe3dca5ff5]
[runnervmvrwv9:06678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe3dcbb0da]
[runnervmvrwv9:06678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe3dca5a55]
[runnervmvrwv9:06678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe3dca5a6f]
[runnervmvrwv9:06678] [ 8] plumed_master(+0x146dd)[0x558e595046dd]
[runnervmvrwv9:06678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe3d82a1ca]
[runnervmvrwv9:06678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe3d82a28b]
[runnervmvrwv9:06678] [11] plumed_master(+0x15365)[0x558e59505365]
[runnervmvrwv9:06678] *** End of error message ***
</pre>
{% endraw %}
