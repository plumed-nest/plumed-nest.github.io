**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmtnos:33901] *** Process received signal ***
[runnervmmtnos:33901] Signal: Aborted (6)
[runnervmmtnos:33901] Signal code:  (-6)
[runnervmmtnos:33901] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f874b245330]
[runnervmmtnos:33901] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f874b29eb2c]
[runnervmmtnos:33901] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f874b24527e]
[runnervmmtnos:33901] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f874b2288ff]
[runnervmmtnos:33901] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f874b6a5ff5]
[runnervmmtnos:33901] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f874b6bb0da]
[runnervmmtnos:33901] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f874b6a5a55]
[runnervmmtnos:33901] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f874b6a5a6f]
[runnervmmtnos:33901] [ 8] plumed(+0x146dd)[0x560f70c386dd]
[runnervmmtnos:33901] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f874b22a1ca]
[runnervmmtnos:33901] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f874b22a28b]
[runnervmmtnos:33901] [11] plumed(+0x15365)[0x560f70c39365]
[runnervmmtnos:33901] *** End of error message ***
</pre>
{% endraw %}
