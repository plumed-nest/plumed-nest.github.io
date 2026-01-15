**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33695] *** Process received signal ***
[runnervmmtnos:33695] Signal: Aborted (6)
[runnervmmtnos:33695] Signal code:  (-6)
[runnervmmtnos:33695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8be645330]
[runnervmmtnos:33695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8be69eb2c]
[runnervmmtnos:33695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8be64527e]
[runnervmmtnos:33695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8be6288ff]
[runnervmmtnos:33695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8beaa5ff5]
[runnervmmtnos:33695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8beabb0da]
[runnervmmtnos:33695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8beaa5a55]
[runnervmmtnos:33695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8beaa5a6f]
[runnervmmtnos:33695] [ 8] plumed(+0x146dd)[0x564d3b02a6dd]
[runnervmmtnos:33695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8be62a1ca]
[runnervmmtnos:33695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8be62a28b]
[runnervmmtnos:33695] [11] plumed(+0x15365)[0x564d3b02b365]
[runnervmmtnos:33695] *** End of error message ***
</pre>
{% endraw %}
