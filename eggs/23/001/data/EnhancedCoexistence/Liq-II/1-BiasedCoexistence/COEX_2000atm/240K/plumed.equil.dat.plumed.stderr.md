**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1665-105:07978] *** Process received signal ***
[fv-az1665-105:07978] Signal: Aborted (6)
[fv-az1665-105:07978] Signal code:  (-6)
[fv-az1665-105:07978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b76045330]
[fv-az1665-105:07978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b7609eb2c]
[fv-az1665-105:07978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b7604527e]
[fv-az1665-105:07978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b760288ff]
[fv-az1665-105:07978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b764a5ff5]
[fv-az1665-105:07978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b764bb0da]
[fv-az1665-105:07978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b764a5a55]
[fv-az1665-105:07978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b764a5a6f]
[fv-az1665-105:07978] [ 8] plumed(+0x146dd)[0x55991bf716dd]
[fv-az1665-105:07978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b7602a1ca]
[fv-az1665-105:07978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b7602a28b]
[fv-az1665-105:07978] [11] plumed(+0x15365)[0x55991bf72365]
[fv-az1665-105:07978] *** End of error message ***
</pre>
{% endraw %}
