Este é um exemplo básico de reprodução de vídeo em 360o, usando a versão mais recente da distribuição principal da A-Frame . Neste exemplo, o vídeo é reproduzido usando o a-videosphereprimitivo como a exibição.

Nota: devido à forma como este vídeo foi criado, a exibição da reprodução é girada 180 graus, de modo que o visualizador pareça se mover para frente em vez de para trás.

Em alguns cenários, principalmente em navegadores móveis, as regras de segurança impedem a reprodução automática do vídeo . Para contornar essa limitação, anexos manipuladores de eventos da janela que tentarão iniciar ou alternar a reprodução com base nas entradas do usuário (aqui especificamente click) .

Página principal


O elemento de vídeo é especificado com uma única fonte possível.

Essa fonte usa o formato MP4 , que é amplamente suportado pelos navegadores disponíveis.

Para máxima compatibilidade, atualmente é recomendável usar o formato MP4, quando possível.

multi-source-detail.html
O elemento de vídeo é especificado com duas fontes possíveis.

O primeiro usa o formato HLS , para os navegadores que oferecem suporte à reprodução nativa de HLS.

O segundo usa o formato MP4 , que é amplamente suportado pelos navegadores disponíveis.

No momento, este arquivo de vídeo não está disponível no formato WebM.

A implementação do navegador selecionará automaticamente qual fonte usar.

Observe que este exemplo não segue a recomendação acima, porque está especificamente tentando exercitar a reprodução nativa de HLS ... o que, como resultado, introduz problemas de compatibilidade com determinadas versões do Safari no momento da escrita.