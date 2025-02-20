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
[fv-az797-511:06210] *** Process received signal ***
[fv-az797-511:06210] Signal: Aborted (6)
[fv-az797-511:06210] Signal code:  (-6)
[fv-az797-511:06210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f205a445330]
[fv-az797-511:06210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f205a49eb2c]
[fv-az797-511:06210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f205a44527e]
[fv-az797-511:06210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f205a4288ff]
[fv-az797-511:06210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f205a8a5ff5]
[fv-az797-511:06210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f205a8bb0da]
[fv-az797-511:06210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f205a8a5a55]
[fv-az797-511:06210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f205a8a5a6f]
[fv-az797-511:06210] [ 8] plumed(+0x146dd)[0x55677e3a56dd]
[fv-az797-511:06210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f205a42a1ca]
[fv-az797-511:06210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f205a42a28b]
[fv-az797-511:06210] [11] plumed(+0x15365)[0x55677e3a6365]
[fv-az797-511:06210] *** End of error message ***
</pre>
{% endraw %}
