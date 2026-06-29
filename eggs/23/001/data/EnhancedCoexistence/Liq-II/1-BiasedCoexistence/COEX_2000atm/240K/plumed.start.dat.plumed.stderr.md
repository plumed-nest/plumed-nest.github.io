**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmmklqx:08427] *** Process received signal ***
[runnervmmklqx:08427] Signal: Aborted (6)
[runnervmmklqx:08427] Signal code:  (-6)
[runnervmmklqx:08427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3773a45330]
[runnervmmklqx:08427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3773a9eb2c]
[runnervmmklqx:08427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3773a4527e]
[runnervmmklqx:08427] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3773a288ff]
[runnervmmklqx:08427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3773ea5ff5]
[runnervmmklqx:08427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3773ebb0da]
[runnervmmklqx:08427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3773ea5a55]
[runnervmmklqx:08427] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3773ea5a6f]
[runnervmmklqx:08427] [ 8] plumed(+0x146dd)[0x5588ab8f96dd]
[runnervmmklqx:08427] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3773a2a1ca]
[runnervmmklqx:08427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3773a2a28b]
[runnervmmklqx:08427] [11] plumed(+0x15365)[0x5588ab8fa365]
[runnervmmklqx:08427] *** End of error message ***
</pre>
{% endraw %}
