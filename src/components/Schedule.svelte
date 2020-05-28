<script>
  import { schedule } from '../data'
</script>

<style>
  .section-title {
    font-size: 32pt;
    font-weight: normal;
    color: #393939;
    padding: 30px 0;
  }
</style>

<section id="schedule" class="container">
  <div class="row">
    <div class="col-md-12">
      <h2 class="section-title">Schedule</h2>
    </div>

    <div class="col-md-12">
      <table class="table table-stripped ">
        <thead class="thead-dark">
          <tr>
            <th scope="col">Time</th>
            <th scope="col">Slot</th>
            <th scope="col">Description</th>
          </tr>
        </thead>
        <tbody>
          {#each schedule as talk}
            <tr>
              <td>{talk.time}</td>
              <td>
                <h4>{talk.speaker}</h4>
                <small>{talk.title}</small>
              </td>
              <td>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo
                </p>
              </td>
            </tr>
          {/each}
        </tbody>
      </table>
    </div>
  </div>
</section>
