**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1392-321:61186] *** Process received signal ***
[fv-az1392-321:61186] Signal: Aborted (6)
[fv-az1392-321:61186] Signal code:  (-6)
[fv-az1392-321:61186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1e1c45330]
[fv-az1392-321:61186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1e1c9eb2c]
[fv-az1392-321:61186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1e1c4527e]
[fv-az1392-321:61186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1e1c288ff]
[fv-az1392-321:61186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1e20a5ff5]
[fv-az1392-321:61186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1e20bb0da]
[fv-az1392-321:61186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1e20a5a55]
[fv-az1392-321:61186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1e20a5a6f]
[fv-az1392-321:61186] [ 8] plumed_master(+0x146dd)[0x561eb9d786dd]
[fv-az1392-321:61186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1e1c2a1ca]
[fv-az1392-321:61186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1e1c2a28b]
[fv-az1392-321:61186] [11] plumed_master(+0x15365)[0x561eb9d79365]
[fv-az1392-321:61186] *** End of error message ***
</pre>
{% endraw %}
