Windows DNS Sunucusu’nun güvenliğini artırmak için kritik öneme sahip olan Socket Pool (Yuva Havuzu) mekanizmasını detaylıca açıklamaktadır. Bu özellik, DNS sunucularının sabit bir kaynak portu kullanmasından kaynaklanan ve saldırganların sahte cevaplar enjekte etmesini kolaylaştıran Önbellek Zehirlenmesi (Cache Poisoning) tehdidini ortadan kaldırmak amacıyla geliştirilmiştir.

<img width="883" height="508" alt="image" src="https://github.com/user-attachments/assets/b7033c59-e336-4051-bcc4-7a787f565e8f" />


It explains in detail the Socket Pool mechanism, which is critical for increasing the security of Windows DNS Server. This feature was developed to eliminate the threat of Cache Poisoning, which is caused by DNS servers using a fixed source port, making it easier for attackers to inject fake responses.
