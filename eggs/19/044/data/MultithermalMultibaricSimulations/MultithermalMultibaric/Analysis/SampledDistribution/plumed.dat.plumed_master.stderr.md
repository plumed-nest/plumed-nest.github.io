**Project ID:** [plumID:19.044]({{ '/' | absolute_url }}eggs/19/044/)  
Stderr for source:  MultithermalMultibaricSimulations/MultithermalMultibaric/Analysis/SampledDistribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[fv-az1392-321:67398] *** Process received signal ***
[fv-az1392-321:67398] Signal: Aborted (6)
[fv-az1392-321:67398] Signal code:  (-6)
[fv-az1392-321:67398] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbcc245330]
[fv-az1392-321:67398] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbcc29eb2c]
[fv-az1392-321:67398] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbcc24527e]
[fv-az1392-321:67398] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbcc2288ff]
[fv-az1392-321:67398] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbcc6a5ff5]
[fv-az1392-321:67398] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbcc6bb0da]
[fv-az1392-321:67398] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbcc6a5a55]
[fv-az1392-321:67398] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbcc6a5a6f]
[fv-az1392-321:67398] [ 8] plumed_master(+0x146dd)[0x5555f6b316dd]
[fv-az1392-321:67398] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbcc22a1ca]
[fv-az1392-321:67398] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbcc22a28b]
[fv-az1392-321:67398] [11] plumed_master(+0x15365)[0x5555f6b32365]
[fv-az1392-321:67398] *** End of error message ***
</pre>
{% endraw %}
