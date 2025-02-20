**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az797-511:06249] *** Process received signal ***
[fv-az797-511:06249] Signal: Aborted (6)
[fv-az797-511:06249] Signal code:  (-6)
[fv-az797-511:06249] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34cbc45330]
[fv-az797-511:06249] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34cbc9eb2c]
[fv-az797-511:06249] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34cbc4527e]
[fv-az797-511:06249] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34cbc288ff]
[fv-az797-511:06249] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34cc0a5ff5]
[fv-az797-511:06249] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34cc0bb0da]
[fv-az797-511:06249] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34cc0a5a55]
[fv-az797-511:06249] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34cc0a5a6f]
[fv-az797-511:06249] [ 8] plumed(+0x146dd)[0x55e3e60ac6dd]
[fv-az797-511:06249] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34cbc2a1ca]
[fv-az797-511:06249] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34cbc2a28b]
[fv-az797-511:06249] [11] plumed(+0x15365)[0x55e3e60ad365]
[fv-az797-511:06249] *** End of error message ***
</pre>
{% endraw %}
