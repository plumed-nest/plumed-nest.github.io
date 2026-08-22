**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervm76f27:08170] *** Process received signal ***
[runnervm76f27:08170] Signal: Aborted (6)
[runnervm76f27:08170] Signal code:  (-6)
[runnervm76f27:08170] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a59845330]
[runnervm76f27:08170] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a5989ec0c]
[runnervm76f27:08170] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a5984527e]
[runnervm76f27:08170] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a598288ff]
[runnervm76f27:08170] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a59ca5ff5]
[runnervm76f27:08170] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a59cbb0da]
[runnervm76f27:08170] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a59ca5a55]
[runnervm76f27:08170] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a59ca5a6f]
[runnervm76f27:08170] [ 8] plumed_master(+0x146dd)[0x55dbc7f156dd]
[runnervm76f27:08170] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a5982a1ca]
[runnervm76f27:08170] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a5982a28b]
[runnervm76f27:08170] [11] plumed_master(+0x15365)[0x55dbc7f16365]
[runnervm76f27:08170] *** End of error message ***
</pre>
{% endraw %}
