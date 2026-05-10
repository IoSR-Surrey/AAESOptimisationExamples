# AAESOptimisationExamples
Audio examples for the paper "Closed-Loop Differentiable Optimisation for Active Acoustics".
Please view this on [GitHub pages](https://iosr-surrey.github.io/AAESOptimisationExamples/).
# Figure 4
Power spectrograms from one test position in the Room 1 16 × 16 AAES comparing the unequalised condition (a) to the open- (b) and closed-loop (c) results.
<div style="display:flex;flex-direction:row;gap:16px;align-items:stretch;">
  <img style="width:400px;height:343px;" alt="Large System Spectrograms" src="https://github.com/user-attachments/assets/6bd6a442-d1e1-4439-b2a1-5d779e70f51f"/>
  <div style="display:flex;flex-direction:column;height:467px;">
    <h2>Impulse Responses</h2>
    <div style="flex:1;display:flex;flex-direction:column;justify-content:space-between;">
      <div>
        <h3>Passive Room</h3>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_passive-room_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>No Equalisation</h3>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_no-eq_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised (Open-Loop)</h3>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_open-loop_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised (Closed-Loop)</h3>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_closed-loop_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;height:467px;">
    <h2>Saxophone Convolution</h2>
    <div style="flex:1;display:flex;flex-direction:column;justify-content:space-between;">
      <div>
        <h3>Passive Room</h3>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_passive-room_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>No Equalisation</h3>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_no-eq_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised (Open-Loop)</h3>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_open-loop_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised (Closed-Loop)</h3>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_closed-loop_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
</div>

# Figure 5
Power spectrograms of (a) the passive RIR of Room 1, (b) the target RIR, and (c) the optimised Room 1 16 × 16 AAES. Dashed white lines indicate the −30 dB profile with half-octave-band resolution.
<div style="display:flex;flex-direction:row;gap:16px;align-items:stretch;">
  <img style="width:400px;height:343px;" alt="EDC Matching Spectrograms" src="https://github.com/user-attachments/assets/0ea4b718-f4fe-43e8-a0a1-5b6799f642cb"/>
  <div style="display:flex;flex-direction:column;height:467px;">
    <h2>Impulse Responses</h2>
    <div style="flex:1;display:flex;flex-direction:column;justify-content:space-between;">
      <div>
        <h3>Passive Room</h3>
        <audio controls>
          <source src="Audio/Fig 5 IRs/passive_room_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Target</h3>
        <audio controls>
          <source src="Audio/Fig 5 IRs/target_room.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised</h3>
        <audio controls>
          <source src="Audio/Fig 5 IRs/16x16_edc_matching_optimised_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised*</h3>
        <audio controls>
          <source src="Audio/Fig 5 IRs/16x16_edc_matching_optimised_early_mod.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;height:467px;">
    <h2>Saxophone Convolution</h2>
    <div style="flex:1;display:flex;flex-direction:column;justify-content:space-between;">
      <div>
        <h3>Passive Room</h3>
        <audio controls>
          <source src="Audio/Fig 5 Conv/passive_room_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Target</h3>
        <audio controls>
          <source src="Audio/Fig 5 Conv/target_room_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised</h3>
        <audio controls>
          <source src="Audio/Fig 5 Conv/16x16_edc_matching_optimised_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h3>Optimised*</h3>
        <audio controls>
          <source src="Audio/Fig 5 Conv/16x16_edc_matching_optimised_early_mod_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
</div>

`*` To provide more comparable early energy, the impulse responses of these examples were constructed by crossfading from the target to the optimised result (between 50 and 100 ms relative to the direct impulse).
