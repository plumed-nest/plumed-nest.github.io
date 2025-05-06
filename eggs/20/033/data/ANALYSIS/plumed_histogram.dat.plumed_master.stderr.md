**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[fv-az1392-321:65916] *** Process received signal ***
[fv-az1392-321:65916] Signal: Aborted (6)
[fv-az1392-321:65916] Signal code:  (-6)
[fv-az1392-321:65916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6705845330]
[fv-az1392-321:65916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f670589eb2c]
[fv-az1392-321:65916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f670584527e]
[fv-az1392-321:65916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67058288ff]
[fv-az1392-321:65916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6705ca5ff5]
[fv-az1392-321:65916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6705cbb0da]
[fv-az1392-321:65916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6705ca5a55]
[fv-az1392-321:65916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6705ca5a6f]
[fv-az1392-321:65916] [ 8] plumed_master(+0x146dd)[0x55dde37496dd]
[fv-az1392-321:65916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f670582a1ca]
[fv-az1392-321:65916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f670582a28b]
[fv-az1392-321:65916] [11] plumed_master(+0x15365)[0x55dde374a365]
[fv-az1392-321:65916] *** End of error message ***
</pre>
{% endraw %}
