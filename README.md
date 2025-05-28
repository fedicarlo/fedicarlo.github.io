# AEGIS - Sistema Autônomo de Bug Hunting

## 🔥 Introdução

O **AEGIS** é um sistema autônomo de Bug Hunting desenvolvido para automatizar processos repetitivos e complexos relacionados à identificação de vulnerabilidades em sistemas e aplicações web.  
Projetado com uma arquitetura **modular** e foco em **integração de ferramentas clássicas de segurança**, aliado a recursos de **inteligência artificial**.

---

## 🚀 Funcionalidades principais

✅ Scans automáticos: Nmap, SQLMap, Ffuf, Subfinder, Nuclei.  
✅ Inferência de vulnerabilidades com IA.  
✅ Relatórios automáticos: TXT, HTML e PDF.  
✅ Backup e compressão automáticos.  
✅ Notificações via Slack.  
✅ Captura de screenshots automatizada.  
✅ Modularidade total — fácil expansão.

---

## ⚙️ Estrutura do projeto

aegis/
├── core/
├── ai/
├── tools/
├── data/
├── auto_runner.py
├── README.md
├── LICENSE
├── requirements.txt

---

## 🛠️ Como instalar

```bash
git clone https://github.com/fedicarlo/fedicarlo.github.io.git
cd aegis
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

▶️ Como executar

python auto_runner.py --alvo https://example.com --modo agressivo

💡 Como colaborar
	1.	Faça um fork do projeto.
	2.	Crie uma branch (git checkout -b feature/nova-funcionalidade).
	3.	Commit suas alterações (git commit -m 'feat: adiciona nova funcionalidade').
	4.	Push para a branch (git push origin feature/nova-funcionalidade).
	5.	Abra um Pull Request.

📜 Licença

Distribuído sob a MIT License.
Veja mais detalhes em LICENSE.

✉️ Contato

Felipe Di Carlo
GitHub
