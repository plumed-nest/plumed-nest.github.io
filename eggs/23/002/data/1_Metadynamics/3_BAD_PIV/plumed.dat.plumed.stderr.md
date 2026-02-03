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
[runnervmkj6or:06457] *** Process received signal ***
[runnervmkj6or:06457] Signal: Aborted (6)
[runnervmkj6or:06457] Signal code:  (-6)
[runnervmkj6or:06457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb24d845330]
[runnervmkj6or:06457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb24d89eb2c]
[runnervmkj6or:06457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb24d84527e]
[runnervmkj6or:06457] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb24d8288ff]
[runnervmkj6or:06457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb24dca5ff5]
[runnervmkj6or:06457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb24dcbb0da]
[runnervmkj6or:06457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb24dca5a55]
[runnervmkj6or:06457] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb24dca5a6f]
[runnervmkj6or:06457] [ 8] plumed(+0x146dd)[0x55b7ca0336dd]
[runnervmkj6or:06457] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb24d82a1ca]
[runnervmkj6or:06457] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb24d82a28b]
[runnervmkj6or:06457] [11] plumed(+0x15365)[0x55b7ca034365]
[runnervmkj6or:06457] *** End of error message ***
</pre>
{% endraw %}
