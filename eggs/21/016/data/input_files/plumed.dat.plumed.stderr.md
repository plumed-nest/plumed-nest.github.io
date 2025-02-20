**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az797-511:07706] *** Process received signal ***
[fv-az797-511:07706] Signal: Aborted (6)
[fv-az797-511:07706] Signal code:  (-6)
[fv-az797-511:07706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f773ce45330]
[fv-az797-511:07706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f773ce9eb2c]
[fv-az797-511:07706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f773ce4527e]
[fv-az797-511:07706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f773ce288ff]
[fv-az797-511:07706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f773d2a5ff5]
[fv-az797-511:07706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f773d2bb0da]
[fv-az797-511:07706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f773d2a5a55]
[fv-az797-511:07706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f773d2a5a6f]
[fv-az797-511:07706] [ 8] plumed(+0x146dd)[0x5572eb1fa6dd]
[fv-az797-511:07706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f773ce2a1ca]
[fv-az797-511:07706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f773ce2a28b]
[fv-az797-511:07706] [11] plumed(+0x15365)[0x5572eb1fb365]
[fv-az797-511:07706] *** End of error message ***
</pre>
{% endraw %}
