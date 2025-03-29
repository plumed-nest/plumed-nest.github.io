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
[fv-az1374-136:63588] *** Process received signal ***
[fv-az1374-136:63588] Signal: Aborted (6)
[fv-az1374-136:63588] Signal code:  (-6)
[fv-az1374-136:63588] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7dc9845330]
[fv-az1374-136:63588] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7dc989eb2c]
[fv-az1374-136:63588] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7dc984527e]
[fv-az1374-136:63588] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7dc98288ff]
[fv-az1374-136:63588] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7dc9ca5ff5]
[fv-az1374-136:63588] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7dc9cbb0da]
[fv-az1374-136:63588] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7dc9ca5a55]
[fv-az1374-136:63588] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7dc9ca5a6f]
[fv-az1374-136:63588] [ 8] plumed(+0x146dd)[0x5628f48ba6dd]
[fv-az1374-136:63588] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7dc982a1ca]
[fv-az1374-136:63588] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7dc982a28b]
[fv-az1374-136:63588] [11] plumed(+0x15365)[0x5628f48bb365]
[fv-az1374-136:63588] *** End of error message ***
</pre>
{% endraw %}
