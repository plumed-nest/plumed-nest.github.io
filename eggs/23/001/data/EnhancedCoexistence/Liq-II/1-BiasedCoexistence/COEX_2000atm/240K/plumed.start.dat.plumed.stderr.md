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
[fv-az1624-565:06480] *** Process received signal ***
[fv-az1624-565:06480] Signal: Aborted (6)
[fv-az1624-565:06480] Signal code:  (-6)
[fv-az1624-565:06480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4384e45330]
[fv-az1624-565:06480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4384e9eb2c]
[fv-az1624-565:06480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4384e4527e]
[fv-az1624-565:06480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4384e288ff]
[fv-az1624-565:06480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43852a5ff5]
[fv-az1624-565:06480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43852bb0da]
[fv-az1624-565:06480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43852a5a55]
[fv-az1624-565:06480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43852a5a6f]
[fv-az1624-565:06480] [ 8] plumed(+0x146dd)[0x557c6838b6dd]
[fv-az1624-565:06480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4384e2a1ca]
[fv-az1624-565:06480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4384e2a28b]
[fv-az1624-565:06480] [11] plumed(+0x15365)[0x557c6838c365]
[fv-az1624-565:06480] *** End of error message ***
</pre>
{% endraw %}
