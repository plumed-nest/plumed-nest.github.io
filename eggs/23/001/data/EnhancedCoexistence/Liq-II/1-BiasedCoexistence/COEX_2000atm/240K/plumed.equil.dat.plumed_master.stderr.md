**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az807-718:62764] *** Process received signal ***
[fv-az807-718:62764] Signal: Aborted (6)
[fv-az807-718:62764] Signal code:  (-6)
[fv-az807-718:62764] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6abc445330]
[fv-az807-718:62764] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6abc49eb2c]
[fv-az807-718:62764] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6abc44527e]
[fv-az807-718:62764] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6abc4288ff]
[fv-az807-718:62764] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6abc8a5ff5]
[fv-az807-718:62764] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6abc8bb0da]
[fv-az807-718:62764] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6abc8a5a55]
[fv-az807-718:62764] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6abc8a5a6f]
[fv-az807-718:62764] [ 8] plumed_master(+0x146dd)[0x557eb0d8c6dd]
[fv-az807-718:62764] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6abc42a1ca]
[fv-az807-718:62764] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6abc42a28b]
[fv-az807-718:62764] [11] plumed_master(+0x15365)[0x557eb0d8d365]
[fv-az807-718:62764] *** End of error message ***
</pre>
{% endraw %}
