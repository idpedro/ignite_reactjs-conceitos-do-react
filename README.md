# Desafio 01 - Conceitos do React

## Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:

- [x] **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- [x] **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- [x] **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.

## Resultado esperado ao executar os testes

```sh
 PASS  src/__tests__/components/TaskList.spec.tsx
  App Page
    ✓ should be able to add a task (73 ms)
    ✓ should not be able to add a task with a empty title (15 ms)
    ✓ should be able to remove a task (27 ms)
    ✓ should be able to check a task (29 ms)

Test Suites: 1 passed, 1 total
Tests:       4 passed, 4 total
Snapshots:   0 total
Time:        2.037 s
Ran all test suites.
```

Desafio finalizado.
