# 핸들과 똑같은 이메일 설정

[kono.pub](https://kono.pub)은 도메인 루트에 있어서 마스토돈에 이름을 설정하면 `@name@kono.pub`의 모양이 됩니다. 그런데 이 핸들에서 맨 앞의 `@`를 뺀 나머지를 그대로 이메일로 사용할 수 있습니다. [연락처](undefined-1.md) 페이지에 있는 `contact@kono.pub` 이메일도 마스토돈 핸들과 이메일이 똑같은 모양입니다.

이 설정은 [클라우드플레어](https://dash.cloudflare.com/)에서 제공하는 이메일 라우팅 기능을 활용하고 있습니다. `kono.pub`으로 끝나는 이메일 주소를 만들고 여기에 원래 사용하는 이메일 주소를 연결해 두면 받은 이메일을 원래 사용하는 이메일 주소로 포워딩 합니다.&#x20;

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

새 메일 계정을 설정하는 것은 귀찮지만 원래 사용하던 이메일 주소로 메일을 포워딩 하면 계정을 새로 만들 필요 없이 그냥 이전에 메일을 확인하던 습관 그대로 사용하면 되니까 편하더라구요. 다만 이메일 포워딩 설정은 지금으로써는 수동으로 할 수밖에 없어서 사용자가 적을 때 원활하게 할 수 있을 것 같습니다.

결론. 마스토돈 핸들과 똑같은 모양의 이메일 주소를 사용하고 싶으신 분은 [연락처](undefined-1.md)를 참고하셔서 개인 메시지를 통해 이메일 주소를 만들어 달라고 요청해 주시면 마스토돈 핸들 모양의 이메일 주소를 만들어등록할 때 사용한 이메일 주소로 연결해 놓겠습니다.

참고로 클라우드플레어 설정에는 제가 이메일을 볼 방법은 전혀 없습니다. 개인정보와 보안 문제는 걱정하지 않으셔도 될 것 같습니다. 또한 [알려진 제약사항](https://developers.cloudflare.com/email-routing/known-limitations/)을 보면 메일을 받을 수는 있지만  이 주소로 메일을 보낼 수는 없습니다.

> [​​](https://developers.cloudflare.com/email-routing/known-limitations/#sending-or-replying-to-an-email-from-your-cloudflare-domain)Sending or replying to an email from your Cloudflare domain
>
> Email Routing does not support sending or replying from your Cloudflare domain. When you reply to emails forwarded by Email Routing, the reply will be sent from your destination address (like `my-name@gmail.com`), not your custom address (like `info@my-company.com`).

