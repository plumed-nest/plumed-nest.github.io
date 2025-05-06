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
[fv-az807-718:62695] *** Process received signal ***
[fv-az807-718:62695] Signal: Aborted (6)
[fv-az807-718:62695] Signal code:  (-6)
[fv-az807-718:62695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8f5845330]
[fv-az807-718:62695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8f589eb2c]
[fv-az807-718:62695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8f584527e]
[fv-az807-718:62695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8f58288ff]
[fv-az807-718:62695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8f5ca5ff5]
[fv-az807-718:62695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8f5cbb0da]
[fv-az807-718:62695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8f5ca5a55]
[fv-az807-718:62695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8f5ca5a6f]
[fv-az807-718:62695] [ 8] plumed(+0x146dd)[0x56458038f6dd]
[fv-az807-718:62695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8f582a1ca]
[fv-az807-718:62695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8f582a28b]
[fv-az807-718:62695] [11] plumed(+0x15365)[0x564580390365]
[fv-az807-718:62695] *** End of error message ***
</pre>
{% endraw %}
