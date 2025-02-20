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
[fv-az797-511:06265] *** Process received signal ***
[fv-az797-511:06265] Signal: Aborted (6)
[fv-az797-511:06265] Signal code:  (-6)
[fv-az797-511:06265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e4a845330]
[fv-az797-511:06265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e4a89eb2c]
[fv-az797-511:06265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e4a84527e]
[fv-az797-511:06265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e4a8288ff]
[fv-az797-511:06265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e4aca5ff5]
[fv-az797-511:06265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e4acbb0da]
[fv-az797-511:06265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e4aca5a55]
[fv-az797-511:06265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e4aca5a6f]
[fv-az797-511:06265] [ 8] plumed_master(+0x146dd)[0x5579c45086dd]
[fv-az797-511:06265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e4a82a1ca]
[fv-az797-511:06265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e4a82a28b]
[fv-az797-511:06265] [11] plumed_master(+0x15365)[0x5579c4509365]
[fv-az797-511:06265] *** End of error message ***
</pre>
{% endraw %}
