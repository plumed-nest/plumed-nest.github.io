**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervmeorf1:08598] *** Process received signal ***
[runnervmeorf1:08598] Signal: Aborted (6)
[runnervmeorf1:08598] Signal code:  (-6)
[runnervmeorf1:08598] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f44c2045330]
[runnervmeorf1:08598] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f44c209eb2c]
[runnervmeorf1:08598] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f44c204527e]
[runnervmeorf1:08598] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44c20288ff]
[runnervmeorf1:08598] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44c24a5ff5]
[runnervmeorf1:08598] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44c24bb0da]
[runnervmeorf1:08598] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44c24a5a55]
[runnervmeorf1:08598] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44c24a5a6f]
[runnervmeorf1:08598] [ 8] plumed(+0x146dd)[0x55562aa3d6dd]
[runnervmeorf1:08598] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f44c202a1ca]
[runnervmeorf1:08598] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f44c202a28b]
[runnervmeorf1:08598] [11] plumed(+0x15365)[0x55562aa3e365]
[runnervmeorf1:08598] *** End of error message ***
</pre>
{% endraw %}
