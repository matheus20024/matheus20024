import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Phone } from "lucide-react";
import "./styles.css";

export default function Portfolio() {
  return (
    <div className="container">
      <div className="content">
        
        {/* Header */}
        <div className="header">
          <h1>Matheus Dantas</h1>
          <p>Assistente Financeiro Freelancer</p>
        </div>

        {/* Sobre */}
        <Card className="card">
          <CardContent>
            <h2>Sobre Mim</h2>
            <p>
              Estou iniciando na área financeira, com foco em controle financeiro,
              organização de planilhas e apoio administrativo. Busco ajudar
              empresas e pessoas a organizarem suas finanças de forma simples e eficiente.
            </p>
          </CardContent>
        </Card>

        {/* Serviços */}
        <Card className="card">
          <CardContent>
            <h2>Serviços</h2>
            <ul>
              <li>Controle financeiro pessoal e empresarial</li>
              <li>Criação de planilhas no Excel</li>
              <li>Organização de despesas e receitas</li>
              <li>Fluxo de caixa</li>
            </ul>
          </CardContent>
        </Card>

        {/* Contato */}
        <Card className="card">
          <CardContent>
            <h2>Contato</h2>
            <p><Mail size={16}/> seuemail@email.com</p>
            <p><Phone size={16}/> (00) 00000-0000</p>
          </CardContent>
        </Card>

        {/* Botão */}
        <div className="button-container">
          <Button>Me Contrate</Button>
        </div>

      </div>
    </div>
  );
}

/* styles.css */

.container {
  min-height: 100vh;
  background: #f3f4f6;
  padding: 20px;
}

.content {
  max-width: 800px;
  margin: 0 auto;
}

.header {
  text-align: center;
  margin-bottom: 20px;
}

.header h1 {
  font-size: 32px;
  margin-bottom: 5px;
}

.header p {
  color: #555;
}

.card {
  background: white;
  border-radius: 16px;
  padding: 15px;
  margin-bottom: 15px;
  box-shadow: 0 2px 8px rgba(0,0,0,
