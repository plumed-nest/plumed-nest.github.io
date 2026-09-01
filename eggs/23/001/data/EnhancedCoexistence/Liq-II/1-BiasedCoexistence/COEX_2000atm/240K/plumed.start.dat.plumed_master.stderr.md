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
[runnervmgx7h7:07489] *** Process received signal ***
[runnervmgx7h7:07489] Signal: Aborted (6)
[runnervmgx7h7:07489] Signal code:  (-6)
[runnervmgx7h7:07489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02df845330]
[runnervmgx7h7:07489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02df89ec0c]
[runnervmgx7h7:07489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02df84527e]
[runnervmgx7h7:07489] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02df8288ff]
[runnervmgx7h7:07489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02dfca5ff5]
[runnervmgx7h7:07489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02dfcbb0da]
[runnervmgx7h7:07489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02dfca5a55]
[runnervmgx7h7:07489] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02dfca5a6f]
[runnervmgx7h7:07489] [ 8] plumed_master(+0x146dd)[0x5623b17966dd]
[runnervmgx7h7:07489] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02df82a1ca]
[runnervmgx7h7:07489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02df82a28b]
[runnervmgx7h7:07489] [11] plumed_master(+0x15365)[0x5623b1797365]
[runnervmgx7h7:07489] *** End of error message ***
</pre>
{% endraw %}
