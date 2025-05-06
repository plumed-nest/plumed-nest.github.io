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
[fv-az807-718:62748] *** Process received signal ***
[fv-az807-718:62748] Signal: Aborted (6)
[fv-az807-718:62748] Signal code:  (-6)
[fv-az807-718:62748] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2bfc45330]
[fv-az807-718:62748] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2bfc9eb2c]
[fv-az807-718:62748] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2bfc4527e]
[fv-az807-718:62748] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2bfc288ff]
[fv-az807-718:62748] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2c00a5ff5]
[fv-az807-718:62748] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2c00bb0da]
[fv-az807-718:62748] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2c00a5a55]
[fv-az807-718:62748] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2c00a5a6f]
[fv-az807-718:62748] [ 8] plumed(+0x146dd)[0x55f0ca1696dd]
[fv-az807-718:62748] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2bfc2a1ca]
[fv-az807-718:62748] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2bfc2a28b]
[fv-az807-718:62748] [11] plumed(+0x15365)[0x55f0ca16a365]
[fv-az807-718:62748] *** End of error message ***
</pre>
{% endraw %}
