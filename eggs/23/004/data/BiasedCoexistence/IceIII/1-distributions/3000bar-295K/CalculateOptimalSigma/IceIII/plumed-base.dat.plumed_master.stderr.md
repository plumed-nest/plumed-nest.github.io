**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1267-279:63667] *** Process received signal ***
[fv-az1267-279:63667] Signal: Aborted (6)
[fv-az1267-279:63667] Signal code:  (-6)
[fv-az1267-279:63667] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d1ca45330]
[fv-az1267-279:63667] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d1ca9eb2c]
[fv-az1267-279:63667] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d1ca4527e]
[fv-az1267-279:63667] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d1ca288ff]
[fv-az1267-279:63667] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d1cea5ff5]
[fv-az1267-279:63667] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d1cebb0da]
[fv-az1267-279:63667] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d1cea5a55]
[fv-az1267-279:63667] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d1cea5a6f]
[fv-az1267-279:63667] [ 8] plumed_master(+0x146dd)[0x563a22f1d6dd]
[fv-az1267-279:63667] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d1ca2a1ca]
[fv-az1267-279:63667] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d1ca2a28b]
[fv-az1267-279:63667] [11] plumed_master(+0x15365)[0x563a22f1e365]
[fv-az1267-279:63667] *** End of error message ***
</pre>
{% endraw %}
