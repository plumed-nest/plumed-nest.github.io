**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1341-704:63256] *** Process received signal ***
[fv-az1341-704:63256] Signal: Aborted (6)
[fv-az1341-704:63256] Signal code:  (-6)
[fv-az1341-704:63256] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3b6445330]
[fv-az1341-704:63256] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3b649eb2c]
[fv-az1341-704:63256] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3b644527e]
[fv-az1341-704:63256] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3b64288ff]
[fv-az1341-704:63256] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3b68a5ff5]
[fv-az1341-704:63256] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3b68bb0da]
[fv-az1341-704:63256] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3b68a5a55]
[fv-az1341-704:63256] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3b68a5a6f]
[fv-az1341-704:63256] [ 8] plumed_master(+0x146dd)[0x562f8dfa06dd]
[fv-az1341-704:63256] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3b642a1ca]
[fv-az1341-704:63256] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3b642a28b]
[fv-az1341-704:63256] [11] plumed_master(+0x15365)[0x562f8dfa1365]
[fv-az1341-704:63256] *** End of error message ***
</pre>
{% endraw %}
