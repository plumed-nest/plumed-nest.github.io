**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33797] *** Process received signal ***
[runnervmmtnos:33797] Signal: Aborted (6)
[runnervmmtnos:33797] Signal code:  (-6)
[runnervmmtnos:33797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb21bc45330]
[runnervmmtnos:33797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21bc9eb2c]
[runnervmmtnos:33797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21bc4527e]
[runnervmmtnos:33797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb21bc288ff]
[runnervmmtnos:33797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb21c0a5ff5]
[runnervmmtnos:33797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb21c0bb0da]
[runnervmmtnos:33797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb21c0a5a55]
[runnervmmtnos:33797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb21c0a5a6f]
[runnervmmtnos:33797] [ 8] plumed(+0x146dd)[0x55c7d5fdc6dd]
[runnervmmtnos:33797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21bc2a1ca]
[runnervmmtnos:33797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21bc2a28b]
[runnervmmtnos:33797] [11] plumed(+0x15365)[0x55c7d5fdd365]
[runnervmmtnos:33797] *** End of error message ***
</pre>
{% endraw %}
