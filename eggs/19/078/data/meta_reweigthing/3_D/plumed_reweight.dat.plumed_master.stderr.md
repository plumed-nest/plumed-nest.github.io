**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/3_D/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=20
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fab3ff144b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fab3ff14428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fab3ff1602a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fab4054e84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fab4054c6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fab4054c701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fab4054c969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fab3feff830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10814] *** End of error message ***
</pre>
{% endraw %}
