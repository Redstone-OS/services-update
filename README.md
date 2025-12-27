# update

Gerenciador de atualizações atômicas.

## O que ele deve ser?
O guardião da integridade do sistema operacional. Ele garante que as atualizações nunca deixem o sistema incapaz de iniciar.

## O que precisa fazer?
- [ ] **Downloads Seguros**: Baixar pacotes de atualização e verificar assinaturas digitais.
- [ ] **Sistema A/B**: Aplicar atualizações em uma partição inativa enquanto o sistema roda.
- [ ] **Snapshots**: Integrar-se ao RFS para criar pontos de restauração antes de mudar algo.
- [ ] **Rollback**: Se o boot falhar após um update, voltar automaticamente para a versão anterior.
