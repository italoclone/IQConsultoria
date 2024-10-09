---
layout: page
title: Contato
tags: [contato, formulario]
date: 2018-01-24
comments: false
---

<div id="contact">
    <h2>Entre em contato</h2>
    <div id="contact-form">
        <form action="https://formspree.io/f/xrbgzdla" method="POST">
            <input type="hidden" name="_subject" value="Formulário de contato IQConsultoria" />
            <input type="email" name="_replyto" placeholder="E-mail" required>
            <textarea name="message" placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>
</div>

<style>
    #contact {
        max-width: 600px;
        margin: 0 auto;
        padding: 20px;
        background-color: #f9f9f9;
        border-radius: 8px;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }

    h2 {
        text-align: center;
        color: #333;
    }

    #contact-form {
        display: flex;
        flex-direction: column;
    }

    input[type="email"], textarea {
        width: 100%;
        padding: 10px;
        margin: 10px 0;
        border: 1px solid #ccc;
        border-radius: 4px;
        font-size: 16px;
        transition: border-color 0.3s;
    }

    input[type="email"]:focus, textarea:focus {
        border-color: #007BFF;
        outline: none;
    }

    button {
        padding: 10px;
        background-color: #007BFF;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s;
    }

    button:hover {
        background-color: #0056b3;
    }
</style>


