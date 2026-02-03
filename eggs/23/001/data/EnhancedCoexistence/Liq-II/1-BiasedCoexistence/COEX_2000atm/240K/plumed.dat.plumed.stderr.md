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
[runnervmkj6or:06868] *** Process received signal ***
[runnervmkj6or:06868] Signal: Aborted (6)
[runnervmkj6or:06868] Signal code:  (-6)
[runnervmkj6or:06868] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7212845330]
[runnervmkj6or:06868] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f721289eb2c]
[runnervmkj6or:06868] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f721284527e]
[runnervmkj6or:06868] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f72128288ff]
[runnervmkj6or:06868] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7212ca5ff5]
[runnervmkj6or:06868] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7212cbb0da]
[runnervmkj6or:06868] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7212ca5a55]
[runnervmkj6or:06868] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7212ca5a6f]
[runnervmkj6or:06868] [ 8] plumed(+0x146dd)[0x5613df3db6dd]
[runnervmkj6or:06868] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f721282a1ca]
[runnervmkj6or:06868] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f721282a28b]
[runnervmkj6or:06868] [11] plumed(+0x15365)[0x5613df3dc365]
[runnervmkj6or:06868] *** End of error message ***
</pre>
{% endraw %}
