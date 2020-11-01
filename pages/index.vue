<template>
  <div>
    <h1>Todoリスト</h1>
    <table>
      <tr>
        <th>内容</th>
        <th>完了</th>
        <th>追加日</th>
      </tr>

    </table>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todos: [
        {
          title: '買い物',
          done: false,
          created_at: new Date()
        },
        {
          title: 'Jsの勉強',
          done: false,
          created_at: new Date()
        },
      ]
    }
  }

}
</script>

<style>
th, td {
  border: 1px solid #ddd;
}
</style>
