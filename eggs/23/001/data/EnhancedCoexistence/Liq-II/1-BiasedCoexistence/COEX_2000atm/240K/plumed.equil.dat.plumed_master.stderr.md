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
[fv-az1370-99:62576] *** Process received signal ***
[fv-az1370-99:62576] Signal: Aborted (6)
[fv-az1370-99:62576] Signal code:  (-6)
[fv-az1370-99:62576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0765845330]
[fv-az1370-99:62576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f076589eb2c]
[fv-az1370-99:62576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f076584527e]
[fv-az1370-99:62576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07658288ff]
[fv-az1370-99:62576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0765ca5ff5]
[fv-az1370-99:62576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0765cbb0da]
[fv-az1370-99:62576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0765ca5a55]
[fv-az1370-99:62576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0765ca5a6f]
[fv-az1370-99:62576] [ 8] plumed_master(+0x146dd)[0x5576d586c6dd]
[fv-az1370-99:62576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f076582a1ca]
[fv-az1370-99:62576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f076582a28b]
[fv-az1370-99:62576] [11] plumed_master(+0x15365)[0x5576d586d365]
[fv-az1370-99:62576] *** End of error message ***
</pre>
{% endraw %}
