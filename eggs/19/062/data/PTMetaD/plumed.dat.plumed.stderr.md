**Project ID:** [plumID:19.062]({{ '/' | absolute_url }}eggs/19/062/)  
Stderr for source:  PTMetaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label cvbias : cannot understand the following words from the input line : REWEIGHTING_NGRID=5001, REWEIGHTING_NHILLS=10
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fafae3504b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fafae350428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fafae35202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fafae98a84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fafae9886b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fafae988701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fafae988919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fafae33b830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13721] *** End of error message ***
</pre>
{% endraw %}
