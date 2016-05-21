# sso-same-domain
Aynı domain altında 2 farklı uygulamanın tek oturum ile yönetilmesi örneği.

mvc ile yapılmış 2 farklı uygulama aynı domain altında tek bir oturum ile çalışası istendiğinde yapmamız gereken web.config altındaki machinekey değerni aynı vermek  ve yine web.config altında form  <forms loginUrl="http://localhost:53859/Home/login" timeout="2880" /> belirlememiz yeterli.
