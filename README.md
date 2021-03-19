# java-teste-8
<%
Response.Write "            <!DOCTYPE HTML PUBLIC ""-//W3C//DTD HTML 4.01 Transitional//EN"">" & vbCrLf
Response.Write "<html>" & vbCrLf
Response.Write "<head>" & vbCrLf
Response.Write "<title>Untitled Document</title>" & vbCrLf
Response.Write "<meta http-equiv=""Content-Type"" content=""text/html"">" & vbCrLf
Response.Write "</head>" & vbCrLf
Response.Write "<body>" & vbCrLf
Response.Write "" & vbCrLf
Response.Write "              package funcionario;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "public class Funcionario {<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    protected int numeroRegistro;<br />" & vbCrLf
Response.Write "    protected String nome;<br />" & vbCrLf
Response.Write "    protected String funcao;<br />" & vbCrLf
Response.Write "    protected float salario;<br />" & vbCrLf
Response.Write "    protected String situacao;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public Funcionario() {<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public Funcionario(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao){<br />" & vbCrLf
Response.Write "        numeroRegistro = _numeroRegistro;<br />" & vbCrLf
Response.Write "        nome = _nome;<br />" & vbCrLf
Response.Write "        funcao = _funcao;<br />" & vbCrLf
Response.Write "        salario = _salario;<br />" & vbCrLf
Response.Write "        situacao = _situacao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirNumeroRegistro(int _numeroRegistro){<br />" & vbCrLf
Response.Write "         numeroRegistro = _numeroRegistro;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public int ObterNumeroRegistro(){<br />" & vbCrLf
Response.Write "        return(numeroRegistro);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirNome(String _nome){<br />" & vbCrLf
Response.Write "        nome = _nome;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterNome(){<br />" & vbCrLf
Response.Write "        return(nome);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirFuncao(String _funcao){<br />" & vbCrLf
Response.Write "        funcao = _funcao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterFuncao(){<br />" & vbCrLf
Response.Write "        return(funcao);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirSalario(float _salario){<br />" & vbCrLf
Response.Write "        salario = _salario;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public float ObterSalario(){<br />" & vbCrLf
Response.Write "        return(salario);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirSituacao(String _situacao){<br />" & vbCrLf
Response.Write "        situacao = _situacao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterSituacao(){<br />" & vbCrLf
Response.Write "        return(situacao);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "}<br />" & vbCrLf
Response.Write "package funcionario;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "public class FuncionarioEfetivo extends Funcionario {<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    private String dataAdmissao;<br />" & vbCrLf
Response.Write "    private String dataDemissao;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioEfetivo() {<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioEfetivo(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao, String _dataAdmissao, String _dataDemissao){<br />" & vbCrLf
Response.Write "        numeroRegistro = _numeroRegistro;<br />" & vbCrLf
Response.Write "        nome = _nome;<br />" & vbCrLf
Response.Write "        funcao = _funcao;<br />" & vbCrLf
Response.Write "        salario = _salario;<br />" & vbCrLf
Response.Write "        situacao = _situacao;<br />" & vbCrLf
Response.Write "        dataAdmissao = _dataAdmissao;<br />" & vbCrLf
Response.Write "        dataDemissao = _dataDemissao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDataAdmissao(String _dataAdmissao){<br />" & vbCrLf
Response.Write "        dataAdmissao = _dataAdmissao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDataAdmissao(){<br />" & vbCrLf
Response.Write "        return(dataAdmissao);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDataDemissao(String _dataDemissao){<br />" & vbCrLf
Response.Write "        dataDemissao = _dataDemissao;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDataDemissao(){<br />" & vbCrLf
Response.Write "        return(dataDemissao);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "}<br />" & vbCrLf
Response.Write "package funcionario;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "public class FuncionarioTemporario extends Funcionario{<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    private String dataInicio;<br />" & vbCrLf
Response.Write "    private String duracaoMeses;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioTemporario() {<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioTemporario(int _numeroRegistro, String _nome, String _funcao, float _salario, String _situacao, String _dataInicio, String _duracaoMeses){<br />" & vbCrLf
Response.Write "        numeroRegistro = _numeroRegistro;<br />" & vbCrLf
Response.Write "        nome = _nome;<br />" & vbCrLf
Response.Write "        funcao = _funcao;<br />" & vbCrLf
Response.Write "        salario = _salario;<br />" & vbCrLf
Response.Write "        situacao = _situacao;<br />" & vbCrLf
Response.Write "        dataInicio = _dataInicio;<br />" & vbCrLf
Response.Write "        duracaoMeses = _duracaoMeses;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDataInicio(String _dataInicio){<br />" & vbCrLf
Response.Write "        dataInicio = _dataInicio;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDataInicio(){<br />" & vbCrLf
Response.Write "        return(dataInicio);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDuracaoMeses(String _duracaoMeses){<br />" & vbCrLf
Response.Write "        duracaoMeses = _duracaoMeses;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDuracaoMeses(){<br />" & vbCrLf
Response.Write "        return(duracaoMeses);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "}<br />" & vbCrLf
Response.Write "package funcionario;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "public class FuncionarioTerceiro extends Funcionario{<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    private String dataInicio;<br />" & vbCrLf
Response.Write "    private String duracaoContrato;<br />" & vbCrLf
Response.Write "    private String nomeEmpresa;<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioTerceiro() {<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public FuncionarioTerceiro(int _numeroRegistro, String _nome,String_botao z entrar e m sair, String _funcao, float _salario, String _situacao, String _dataInicio, String _duracaoContrato, String _nomeEmpresa){<br />" & vbCrLf
Response.Write "        numeroRegistro = _numeroRegistro;<br />" & vbCrLf
Response.Write "        nome = _nome;<br />" & vbCrLf
Response.Write "        funcao = _funcao;<br />" & vbCrLf
Response.Write "        salario = _salario;<br />" & vbCrLf
Response.Write "        situacao = _situacao;<br />" & vbCrLf
Response.Write "        dataInicio = _dataInicio;<br />" & vbCrLf
Response.Write "        duracaoContrato = _duracaoContrato;<br />" & vbCrLf
Response.Write "        nomeEmpresa = _nomeEmpresa;<br />" & vbCrLf
Response.Write "        botaoacesso = botaoacesso;<br />" & vbCrLf
Response.Write "        { public void definirbotaoacesso(z entar e m sair)}<br />" & vbCrLf
Response.Write "        botaoacesso=botaoacesso;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDataInicio(String _dataInicio){<br />" & vbCrLf
Response.Write "        dataInicio = _dataInicio;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDataInicio(){<br />" & vbCrLf
Response.Write "        return(dataInicio);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirDuracaoContrato(String _duracaoContrato){<br />" & vbCrLf
Response.Write "        duracaoContrato = _duracaoContrato;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterDuracaoContrato(){<br />" & vbCrLf
Response.Write "        return(duracaoContrato);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public void DefinirNomeEmpresa(String _nomeEmpresa){<br />" & vbCrLf
Response.Write "        nomeEmpresa = _nomeEmpresa;<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "    public String ObterNomeEmpresa(){<br />" & vbCrLf
Response.Write "        return(nomeEmpresa);<br />" & vbCrLf
Response.Write "    }<br />" & vbCrLf
Response.Write "<br />" & vbCrLf
Response.Write "}<br />" & vbCrLf
Response.Write "" & vbCrLf
Response.Write "<!-- Converted by 0-Code HTML Converter - Trial Version -->" & vbCrLf
Response.Write "" & vbCrLf
Response.Write "</body>" & vbCrLf
Response.Write "</html>" & vbCrLf
Response.Write ""
%>

<!-- Converted by 0-Code HTML Converter - Trial Version -->
