**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[fv-az807-718:62711] *** Process received signal ***
[fv-az807-718:62711] Signal: Aborted (6)
[fv-az807-718:62711] Signal code:  (-6)
[fv-az807-718:62711] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed91645330]
[fv-az807-718:62711] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed9169eb2c]
[fv-az807-718:62711] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed9164527e]
[fv-az807-718:62711] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed916288ff]
[fv-az807-718:62711] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed91aa5ff5]
[fv-az807-718:62711] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed91abb0da]
[fv-az807-718:62711] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed91aa5a55]
[fv-az807-718:62711] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed91aa5a6f]
[fv-az807-718:62711] [ 8] plumed_master(+0x146dd)[0x55ec614e86dd]
[fv-az807-718:62711] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed9162a1ca]
[fv-az807-718:62711] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed9162a28b]
[fv-az807-718:62711] [11] plumed_master(+0x15365)[0x55ec614e9365]
[fv-az807-718:62711] *** End of error message ***
</pre>
{% endraw %}
