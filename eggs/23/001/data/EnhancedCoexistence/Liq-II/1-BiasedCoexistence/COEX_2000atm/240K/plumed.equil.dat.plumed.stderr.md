**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmgx7h7:07370] *** Process received signal ***
[runnervmgx7h7:07370] Signal: Aborted (6)
[runnervmgx7h7:07370] Signal code:  (-6)
[runnervmgx7h7:07370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f09c0845330]
[runnervmgx7h7:07370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f09c089ec0c]
[runnervmgx7h7:07370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f09c084527e]
[runnervmgx7h7:07370] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09c08288ff]
[runnervmgx7h7:07370] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09c0ca5ff5]
[runnervmgx7h7:07370] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09c0cbb0da]
[runnervmgx7h7:07370] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09c0ca5a55]
[runnervmgx7h7:07370] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09c0ca5a6f]
[runnervmgx7h7:07370] [ 8] plumed(+0x146dd)[0x55d279f066dd]
[runnervmgx7h7:07370] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f09c082a1ca]
[runnervmgx7h7:07370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f09c082a28b]
[runnervmgx7h7:07370] [11] plumed(+0x15365)[0x55d279f07365]
[runnervmgx7h7:07370] *** End of error message ***
</pre>
{% endraw %}
