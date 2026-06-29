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
[runnervmmklqx:08376] *** Process received signal ***
[runnervmmklqx:08376] Signal: Aborted (6)
[runnervmmklqx:08376] Signal code:  (-6)
[runnervmmklqx:08376] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8bd845330]
[runnervmmklqx:08376] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8bd89eb2c]
[runnervmmklqx:08376] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8bd84527e]
[runnervmmklqx:08376] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8bd8288ff]
[runnervmmklqx:08376] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8bdca5ff5]
[runnervmmklqx:08376] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8bdcbb0da]
[runnervmmklqx:08376] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8bdca5a55]
[runnervmmklqx:08376] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8bdca5a6f]
[runnervmmklqx:08376] [ 8] plumed(+0x146dd)[0x556b65a106dd]
[runnervmmklqx:08376] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8bd82a1ca]
[runnervmmklqx:08376] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8bd82a28b]
[runnervmmklqx:08376] [11] plumed(+0x15365)[0x556b65a11365]
[runnervmmklqx:08376] *** End of error message ***
</pre>
{% endraw %}
