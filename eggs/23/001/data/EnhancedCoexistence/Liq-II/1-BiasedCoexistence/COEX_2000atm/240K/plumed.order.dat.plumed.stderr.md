**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmkj6or:06971] *** Process received signal ***
[runnervmkj6or:06971] Signal: Aborted (6)
[runnervmkj6or:06971] Signal code:  (-6)
[runnervmkj6or:06971] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff63f045330]
[runnervmkj6or:06971] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff63f09eb2c]
[runnervmkj6or:06971] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff63f04527e]
[runnervmkj6or:06971] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff63f0288ff]
[runnervmkj6or:06971] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff63f4a5ff5]
[runnervmkj6or:06971] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff63f4bb0da]
[runnervmkj6or:06971] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff63f4a5a55]
[runnervmkj6or:06971] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff63f4a5a6f]
[runnervmkj6or:06971] [ 8] plumed(+0x146dd)[0x5598f73406dd]
[runnervmkj6or:06971] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff63f02a1ca]
[runnervmkj6or:06971] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff63f02a28b]
[runnervmkj6or:06971] [11] plumed(+0x15365)[0x5598f7341365]
[runnervmkj6or:06971] *** End of error message ***
</pre>
{% endraw %}
