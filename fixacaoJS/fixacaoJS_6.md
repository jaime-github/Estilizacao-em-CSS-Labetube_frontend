``` javascript
const apenasTarefasDone = tarefas.filter((realizadas) => {
      return realizadas.status === "done"
  })

const tarefasFiltradas = apenasTarefasDone.map((nomes) => {
      return nomes.titulo
  })
      return tarefasFiltradas
}

```
