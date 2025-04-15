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
[fv-az1370-99:62560] *** Process received signal ***
[fv-az1370-99:62560] Signal: Aborted (6)
[fv-az1370-99:62560] Signal code:  (-6)
[fv-az1370-99:62560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9513445330]
[fv-az1370-99:62560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f951349eb2c]
[fv-az1370-99:62560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f951344527e]
[fv-az1370-99:62560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95134288ff]
[fv-az1370-99:62560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95138a5ff5]
[fv-az1370-99:62560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95138bb0da]
[fv-az1370-99:62560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95138a5a55]
[fv-az1370-99:62560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95138a5a6f]
[fv-az1370-99:62560] [ 8] plumed(+0x146dd)[0x560bbef056dd]
[fv-az1370-99:62560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f951342a1ca]
[fv-az1370-99:62560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f951342a28b]
[fv-az1370-99:62560] [11] plumed(+0x15365)[0x560bbef06365]
[fv-az1370-99:62560] *** End of error message ***
</pre>
{% endraw %}
