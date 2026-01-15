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
[runnervmmtnos:34544] *** Process received signal ***
[runnervmmtnos:34544] Signal: Aborted (6)
[runnervmmtnos:34544] Signal code:  (-6)
[runnervmmtnos:34544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcad7c45330]
[runnervmmtnos:34544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcad7c9eb2c]
[runnervmmtnos:34544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcad7c4527e]
[runnervmmtnos:34544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcad7c288ff]
[runnervmmtnos:34544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcad80a5ff5]
[runnervmmtnos:34544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcad80bb0da]
[runnervmmtnos:34544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcad80a5a55]
[runnervmmtnos:34544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcad80a5a6f]
[runnervmmtnos:34544] [ 8] plumed(+0x146dd)[0x564e72eb26dd]
[runnervmmtnos:34544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcad7c2a1ca]
[runnervmmtnos:34544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcad7c2a28b]
[runnervmmtnos:34544] [11] plumed(+0x15365)[0x564e72eb3365]
[runnervmmtnos:34544] *** End of error message ***
</pre>
{% endraw %}
