**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervm76f27:08272] *** Process received signal ***
[runnervm76f27:08272] Signal: Aborted (6)
[runnervm76f27:08272] Signal code:  (-6)
[runnervm76f27:08272] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc97c245330]
[runnervm76f27:08272] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc97c29ec0c]
[runnervm76f27:08272] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc97c24527e]
[runnervm76f27:08272] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc97c2288ff]
[runnervm76f27:08272] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc97c6a5ff5]
[runnervm76f27:08272] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc97c6bb0da]
[runnervm76f27:08272] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc97c6a5a55]
[runnervm76f27:08272] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc97c6a5a6f]
[runnervm76f27:08272] [ 8] plumed_master(+0x146dd)[0x562f3e8b46dd]
[runnervm76f27:08272] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc97c22a1ca]
[runnervm76f27:08272] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc97c22a28b]
[runnervm76f27:08272] [11] plumed_master(+0x15365)[0x562f3e8b5365]
[runnervm76f27:08272] *** End of error message ***
</pre>
{% endraw %}
