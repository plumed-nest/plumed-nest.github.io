**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/2_D/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ITRE LABEL=it ARG=cc.logweights TEMP=1 MAXITER=20
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f4e036e04b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f4e036e0428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f4e036e202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f4e03d1a84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f4e03d186b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f4e03d18701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f4e03d18919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f4e036cb830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10788] *** End of error message ***
</pre>
{% endraw %}
