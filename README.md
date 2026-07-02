```
 █████╗ ██╗   ██╗████████╗ ██████╗      ██████╗ ███████╗██████╗ 
██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗    ██╔════╝ ██╔════╝██╔══██╗
███████║██║   ██║   ██║   ██║   ██║    ██║  ███╗███████╗██║  ██║
██╔══██║██║   ██║   ██║   ██║   ██║    ██║   ██║╚════██║██║  ██║
██║  ██║╚██████╔╝   ██║   ╚██████╔╝    ╚██████╔╝███████║██████╔╝
╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝      ╚═════╝ ╚══════╝╚═════╝
   ```                                                                



<b>AUTO GSD</b> é um script de instalação automatizada que configura <i>MySQL Server</i>, <i>Zabbix Server</i> e <i>Grafana</i> em sistemas Ubuntu, com interface colorida e execução em tempo real no terminal.

Indicado para profissionais de infraestrutura, DevOps e analistas de NOC que precisam montar ambientes de monitoramento — em laboratório ou produção — de forma rápida e confiável.
<br/><br/><br/>

📂 <b>Como Utilizar</b>
```bash
git clone https://github.com/sdias-guilherme/zabiix-grafana.git
cd zabiix-grafana
chmod +x automzg.sh
sudo ./automzg.sh
```
<br/><br/>
🔧 <b>Pré-requisitos</b>

→ Ubuntu 22.04 ou superior.<br/>
→ Permissões de root (sudo).<br/>
→ Conexão com a internet.
<br/><br/><br/>
✅ <b>Recursos do Script</b>

→  Detecção de erros e supressão de mensagens desnecessárias.<br/>
→ Configuração automática do repositório Zabbix<br/>
→ Instalação dos pacotes Zabbix Server, Frontend e Agent.<br/>
→ Instalação do MySQL Server.<br/>
→ Instalação do Grafana.<br/>
→ Criação do banco de dados Zabbix com permissões necessárias.<br/>
→ Configuração do arquivo zabbix_server.conf.<br/>
→ Configuração de locale para pt_PT.UTF-8<br/>
→ Ativação utomática dos serviços.<br/>
→ Exibição em tempo real com status de sucesso ou falha.<br/>
→ Instalação completa com um único script, sem configuração manual.
<br/><br/><br/>
🤝 <b>Contribuições</b>

→ Sinta-se livre para enviar críticas, dúvidas ou sugerir melhorias!<br/>
→ Este projeto é open source e feito para a comunidade.<br/>
<br/><br/>
🧑‍💻 Profissionais apaixonados por automação, monitoramento e infraestrutura inteligente.<br/><br/>
🪲 Desenvolvido por <b>BUG IT</b>

<b>Créditos</b>

Este projeto é baseado no [AutoMZG](https://github.com/bug-it/AutoMZG), desenvolvido por BUG IT, com adaptações para locale pt-PT, fuso horário de Lisboa e outras melhorias<br/>
