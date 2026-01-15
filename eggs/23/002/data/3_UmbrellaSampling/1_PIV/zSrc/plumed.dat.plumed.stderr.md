**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33849] *** Process received signal ***
[runnervmmtnos:33849] Signal: Aborted (6)
[runnervmmtnos:33849] Signal code:  (-6)
[runnervmmtnos:33849] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ad7045330]
[runnervmmtnos:33849] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ad709eb2c]
[runnervmmtnos:33849] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ad704527e]
[runnervmmtnos:33849] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ad70288ff]
[runnervmmtnos:33849] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ad74a5ff5]
[runnervmmtnos:33849] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ad74bb0da]
[runnervmmtnos:33849] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ad74a5a55]
[runnervmmtnos:33849] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ad74a5a6f]
[runnervmmtnos:33849] [ 8] plumed(+0x146dd)[0x5622c885e6dd]
[runnervmmtnos:33849] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ad702a1ca]
[runnervmmtnos:33849] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ad702a28b]
[runnervmmtnos:33849] [11] plumed(+0x15365)[0x5622c885f365]
[runnervmmtnos:33849] *** End of error message ***
</pre>
{% endraw %}
