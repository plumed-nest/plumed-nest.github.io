**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1624-565:06496] *** Process received signal ***
[fv-az1624-565:06496] Signal: Aborted (6)
[fv-az1624-565:06496] Signal code:  (-6)
[fv-az1624-565:06496] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba3c845330]
[fv-az1624-565:06496] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba3c89eb2c]
[fv-az1624-565:06496] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba3c84527e]
[fv-az1624-565:06496] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba3c8288ff]
[fv-az1624-565:06496] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba3cca5ff5]
[fv-az1624-565:06496] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba3ccbb0da]
[fv-az1624-565:06496] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba3cca5a55]
[fv-az1624-565:06496] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba3cca5a6f]
[fv-az1624-565:06496] [ 8] plumed_master(+0x146dd)[0x564973d266dd]
[fv-az1624-565:06496] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba3c82a1ca]
[fv-az1624-565:06496] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba3c82a28b]
[fv-az1624-565:06496] [11] plumed_master(+0x15365)[0x564973d27365]
[fv-az1624-565:06496] *** End of error message ***
</pre>
{% endraw %}
