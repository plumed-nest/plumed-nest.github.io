**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervm76f27:08206] *** Process received signal ***
[runnervm76f27:08206] Signal: Aborted (6)
[runnervm76f27:08206] Signal code:  (-6)
[runnervm76f27:08206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a98c45330]
[runnervm76f27:08206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a98c9ec0c]
[runnervm76f27:08206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a98c4527e]
[runnervm76f27:08206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a98c288ff]
[runnervm76f27:08206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a990a5ff5]
[runnervm76f27:08206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a990bb0da]
[runnervm76f27:08206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a990a5a55]
[runnervm76f27:08206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a990a5a6f]
[runnervm76f27:08206] [ 8] plumed(+0x146dd)[0x5580e74e86dd]
[runnervm76f27:08206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a98c2a1ca]
[runnervm76f27:08206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a98c2a28b]
[runnervm76f27:08206] [11] plumed(+0x15365)[0x5580e74e9365]
[runnervm76f27:08206] *** End of error message ***
</pre>
{% endraw %}
