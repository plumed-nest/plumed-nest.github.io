**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[fv-az1665-105:07935] *** Process received signal ***
[fv-az1665-105:07935] Signal: Aborted (6)
[fv-az1665-105:07935] Signal code:  (-6)
[fv-az1665-105:07935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd59f245330]
[fv-az1665-105:07935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd59f29eb2c]
[fv-az1665-105:07935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd59f24527e]
[fv-az1665-105:07935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd59f2288ff]
[fv-az1665-105:07935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd59f6a5ff5]
[fv-az1665-105:07935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd59f6bb0da]
[fv-az1665-105:07935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd59f6a5a55]
[fv-az1665-105:07935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd59f6a5a6f]
[fv-az1665-105:07935] [ 8] plumed(+0x146dd)[0x5576a55fe6dd]
[fv-az1665-105:07935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd59f22a1ca]
[fv-az1665-105:07935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd59f22a28b]
[fv-az1665-105:07935] [11] plumed(+0x15365)[0x5576a55ff365]
[fv-az1665-105:07935] *** End of error message ***
</pre>
{% endraw %}
