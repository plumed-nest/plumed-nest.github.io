**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az789-879:61914] *** Process received signal ***
[fv-az789-879:61914] Signal: Aborted (6)
[fv-az789-879:61914] Signal code:  (-6)
[fv-az789-879:61914] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb12645330]
[fv-az789-879:61914] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb1269eb2c]
[fv-az789-879:61914] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb1264527e]
[fv-az789-879:61914] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb126288ff]
[fv-az789-879:61914] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb12aa5ff5]
[fv-az789-879:61914] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb12abb0da]
[fv-az789-879:61914] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb12aa5a55]
[fv-az789-879:61914] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb12aa5a6f]
[fv-az789-879:61914] [ 8] plumed(+0x146dd)[0x559e3a13e6dd]
[fv-az789-879:61914] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb1262a1ca]
[fv-az789-879:61914] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb1262a28b]
[fv-az789-879:61914] [11] plumed(+0x15365)[0x559e3a13f365]
[fv-az789-879:61914] *** End of error message ***
</pre>
{% endraw %}
