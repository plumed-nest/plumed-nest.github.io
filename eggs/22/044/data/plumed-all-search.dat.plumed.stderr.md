**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervm76f27:08354] *** Process received signal ***
[runnervm76f27:08354] Signal: Aborted (6)
[runnervm76f27:08354] Signal code:  (-6)
[runnervm76f27:08354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff23d645330]
[runnervm76f27:08354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff23d69ec0c]
[runnervm76f27:08354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff23d64527e]
[runnervm76f27:08354] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff23d6288ff]
[runnervm76f27:08354] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff23daa5ff5]
[runnervm76f27:08354] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff23dabb0da]
[runnervm76f27:08354] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff23daa5a55]
[runnervm76f27:08354] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff23daa5a6f]
[runnervm76f27:08354] [ 8] plumed(+0x146dd)[0x559895a976dd]
[runnervm76f27:08354] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff23d62a1ca]
[runnervm76f27:08354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff23d62a28b]
[runnervm76f27:08354] [11] plumed(+0x15365)[0x559895a98365]
[runnervm76f27:08354] *** End of error message ***
</pre>
{% endraw %}
