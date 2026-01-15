**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmmtnos:34648] *** Process received signal ***
[runnervmmtnos:34648] Signal: Aborted (6)
[runnervmmtnos:34648] Signal code:  (-6)
[runnervmmtnos:34648] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56a4245330]
[runnervmmtnos:34648] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56a429eb2c]
[runnervmmtnos:34648] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56a424527e]
[runnervmmtnos:34648] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56a42288ff]
[runnervmmtnos:34648] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56a46a5ff5]
[runnervmmtnos:34648] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56a46bb0da]
[runnervmmtnos:34648] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56a46a5a55]
[runnervmmtnos:34648] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56a46a5a6f]
[runnervmmtnos:34648] [ 8] plumed(+0x146dd)[0x562079eec6dd]
[runnervmmtnos:34648] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56a422a1ca]
[runnervmmtnos:34648] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56a422a28b]
[runnervmmtnos:34648] [11] plumed(+0x15365)[0x562079eed365]
[runnervmmtnos:34648] *** End of error message ***
</pre>
{% endraw %}
