**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1047-397:63324] *** Process received signal ***
[fv-az1047-397:63324] Signal: Aborted (6)
[fv-az1047-397:63324] Signal code:  (-6)
[fv-az1047-397:63324] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f677bc45330]
[fv-az1047-397:63324] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f677bc9eb2c]
[fv-az1047-397:63324] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f677bc4527e]
[fv-az1047-397:63324] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f677bc288ff]
[fv-az1047-397:63324] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f677c0a5ff5]
[fv-az1047-397:63324] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f677c0bb0da]
[fv-az1047-397:63324] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f677c0a5a55]
[fv-az1047-397:63324] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f677c0a5a6f]
[fv-az1047-397:63324] [ 8] plumed_master(+0x146dd)[0x555ecd94a6dd]
[fv-az1047-397:63324] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f677bc2a1ca]
[fv-az1047-397:63324] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f677bc2a28b]
[fv-az1047-397:63324] [11] plumed_master(+0x15365)[0x555ecd94b365]
[fv-az1047-397:63324] *** End of error message ***
</pre>
{% endraw %}
