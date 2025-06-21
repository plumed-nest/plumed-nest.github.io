**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmxyh4eaekms:08511] *** Process received signal ***
[pkrvmxyh4eaekms:08511] Signal: Aborted (6)
[pkrvmxyh4eaekms:08511] Signal code:  (-6)
[pkrvmxyh4eaekms:08511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe750445330]
[pkrvmxyh4eaekms:08511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe75049eb2c]
[pkrvmxyh4eaekms:08511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe75044527e]
[pkrvmxyh4eaekms:08511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe7504288ff]
[pkrvmxyh4eaekms:08511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe7508a5ff5]
[pkrvmxyh4eaekms:08511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe7508bb0da]
[pkrvmxyh4eaekms:08511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe7508a5a55]
[pkrvmxyh4eaekms:08511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe7508a5a6f]
[pkrvmxyh4eaekms:08511] [ 8] plumed(+0x146dd)[0x559e331f76dd]
[pkrvmxyh4eaekms:08511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe75042a1ca]
[pkrvmxyh4eaekms:08511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe75042a28b]
[pkrvmxyh4eaekms:08511] [11] plumed(+0x15365)[0x559e331f8365]
[pkrvmxyh4eaekms:08511] *** End of error message ***
</pre>
{% endraw %}
